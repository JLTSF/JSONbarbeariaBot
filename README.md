Baixe o arquivo JSON em sua máquina
Selecione o bot conectado ao roteador.
Selecione "Configuração"

![image](https://github.com/JLTSF/JSONbarbeariaBot/assets/72716399/a6fb18e1-8839-4c8b-9a55-4c3225f791ab)

Em seguida selecione "Versões" e "Carregar fluxo"

![image](https://github.com/JLTSF/JSONbarbeariaBot/assets/72716399/889cf7c5-2ffd-4069-ad95-743f12060643)

Selecione o arquivo JSON baixado e foguetinho🚀

### Vale lembrar que no momento em que você for testar o Bot a API pode ter mudado ou está fora do ar...
Como toda nossa lógica de agendamento, alteração e cancelamento de horário está na API,
pode ser que o fluxo não seja executado corretamente. Estarei disponibilizando o Endpoint da API para que consigam testar no dia 20/10 a partir das 12hr até as 23:59.

No momento essa API está em fase de teste e conectada a minha agenda pessoal, por esse e outros motivos não poderia disponibilizá-la ainda para vocês.
Aos que se sentirem desafiados e quiserem fazer sua própria API recomendo ler bem a documentação: https://developers.google.com/calendar/api/v3/reference?hl=pt-br

Adicione o endpoint nas "Variáveis de configuração", vá até "Configuração"
e em seguida "Variáveis de configuração" no canto inferior direito, selecione "Adicionar informaçôes extras"
Na esquerda escreva "api", na direita o nosso endpoint e foguetinho 🚀.

![image](https://github.com/JLTSF/JSONbarbeariaBot/assets/72716399/5844b4f2-85ac-4fa2-94b2-0d654fcbfb2a)


### Confira se o Endpoint está igual ao disponibilizado aqui neste passo a passo "https://4816-45-4-146-253.ngrok-free.app/calendar"
GET /getAvailableTimes/range "(range: number) busca os horários livres na agenda em um determinado range de dias, caso não passe um valor, por padrão é 7 dias."
GET /getEventConfirmed/range "(range: number) busca os horários marcados na agenda em um determinado range de dias, caso não passe um valor, por padrão é 7 dias."
POST /createdEvent "cria um evento na agenda, necessário passar os seguintes parametros."
{
  "summary": "string",
  "start": {"dateTime":"new Date()"},
  "end": {"dateTime":"new Date()"}
}

![image](https://github.com/JLTSF/JSONbarbeariaBot/assets/72716399/a0bbec26-b203-43d4-99b3-b5967015318d)

Vocês tambem podem testar o bot indo nessa vidraça quimica ⚗️ e selecionando "Testar chatbot publicado"
e uma tela para interagir com o chatbot devera aparecer na tela.

![image](https://github.com/JLTSF/JSONbarbeariaBot/assets/72716399/1e1fae33-e44f-49f4-9e09-75935eef3d81)
![image](https://github.com/JLTSF/JSONbarbeariaBot/assets/72716399/643f3459-8b1c-4a19-8357-5ba6076a3ce3)



