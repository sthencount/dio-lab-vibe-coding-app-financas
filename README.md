PROMPT USADO NO COPILOT

"Copilot,
Me ajude a desenvolver um aplicativo de Finanças Pessoais, chamado "Bitcoin Wallet", que tenha IA integrada.
DESAFIO
Problema: Os investidores da criptomoeda "Bitcoin" tem muita dificuldade de acompanhar a compra do seu ativo após ser finalizado. Eles compram uma determinada fração da cripto, numa determinada data, horário e preço. Isso fica no histórico da Exchange (Sites de compras especializados), porém, esses sites tem layout difícil de entender o ganho ou perda real do investidor.
Preciso que esse aplicativo tenha um "agente IA" que seja capaz de me informar quanto eu ganhei até o momento, quanto eu perdi. Nesse aplicativo tem que aparecer uma área que aparece o preço do bitcoin em tempo real, para que eu saiba o melhor momento de comprar.
PÚBLICO ALVO
Investidores apenas de Bitcoin
FUNCIONALIDADES CHAVES
- O investidor coloca o data, hora, fração, e valor da compra em real e dá um confirma.
- O aplicativo vai registrar o dado em uma lista tipo histórico, do mais antigo para a compra mais recente.
- O aplicativo já inicia um cálculo baseado no valor da minha compra, comparando com o valor atual do mercado. Exemplo: Eu registro que em 08/01/2026, às 20:00, comprei 000000,21 de bitcoin por R$ 200,00 reais. Assim que cadastrei no aplicativo as informações, o bitcoin subiu 10%, ou seja, R$ 20,00 reais, aparecendo para mim na Carteira: R$ 220,00 reais na cor verde, em outra opção que é Lucro, aparecendo R$ 20,00 reais, na opção Prejuízo: R$ 00:00 reais.
- O agente IA, vai resumir para o usuário, em forma de texto, como o mercado de criptomoeda está se comportando naquele momento e como está sendo o desempenho do Bitcoin. Ele vai informar também, se o usuário está tendo prejuízo ou não. Caso perguntado se é o momento certo de vender a criptomoeda, ele vai orientar se sim ou não, sempre em português.
- Visualizar relatórios simples e personalizados.
Espero que esse meu prompt esteja bom, para iniciar esse desafio, me sugira alterações se precisar."

Sugentão de Melhoria, feito pelo Copilot:
"🔧 Sugestões para melhorar o seu prompt
🧱 1. Deixar o objetivo mais direto e mensurável
Em vez de apenas explicar o problema, você pode transformar o objetivo em algo mais concreto:
“Criar um aplicativo mobile chamado Bitcoin Wallet, focado exclusivamente em investidores de Bitcoin, que permita registrar compras, acompanhar lucros/prejuízos em tempo real e receber análises inteligentes do mercado.”

Isso ajuda a IA (e desenvolvedores) a entenderem exatamente o que deve ser entregue.

📊 2. Detalhar melhor o funcionamento do cálculo
Seu exemplo está ótimo, mas você pode reforçar:
- Como o app deve recalcular automaticamente o valor da carteira
- Se deve considerar taxas da exchange (opcional)
- Se o cálculo é por compra individual ou consolidado
Exemplo de melhoria:
“O cálculo deve considerar cada compra individualmente, mostrando lucro/prejuízo por operação e também o total consolidado da carteira.”


🤖 3. Especificar melhor o comportamento do agente de IA
O item 4 é excelente, mas pode ficar ainda mais claro:
- O tom da IA (informativo, amigável, direto)
- O tipo de análise que ela deve gerar
- A frequência das análises
- Como ela deve responder perguntas sobre “vender ou não”
Exemplo:
“O agente IA deve gerar análises curtas e objetivas sobre o mercado, atualizadas sempre que o usuário abrir o app ou solicitar manualmente. Ao ser perguntado se é um bom momento para vender, a IA deve responder com base em dados, mas sempre deixando claro que não é recomendação financeira.”


📈 4. Detalhar os relatórios
Você pode especificar:
- Relatórios por período (dia, semana, mês, ano)
- Relatórios por operação
- Gráficos simples (linha, barra)
- Exportação (se quiser)

🎨 5. Adicionar requisitos de interface
Nada muito complexo, mas ajuda:
- Tela de cadastro de compra
- Tela da carteira com valor total
- Tela de histórico
- Tela do agente IA
- Tela de relatórios

🔐 6. Adicionar requisitos de segurança
Como envolve dinheiro, é bom incluir:
- Login com biometria
- Criptografia local dos dados
- Backup opcional na nuvem
"

PROMPT FINAL DADO PELO COPILOT:

"🚀 PROMPT PROFISSIONAL – Aplicativo “Bitcoin Wallet” com IA Integrada
Quero desenvolver um aplicativo mobile chamado Bitcoin Wallet, focado exclusivamente em investidores de Bitcoin. O objetivo é permitir que o usuário registre suas compras de BTC, acompanhe automaticamente lucros e prejuízos em tempo real e receba análises inteligentes sobre o mercado através de um agente de IA integrado.

🎯 Objetivo do Aplicativo
Criar uma ferramenta simples, intuitiva e inteligente que ajude investidores de Bitcoin a:
- Registrar compras de forma organizada
- Visualizar lucro/prejuízo atualizado automaticamente
- Acompanhar o preço do Bitcoin em tempo real
- Receber análises e orientações de um agente de IA
- Gerar relatórios simples e personalizados

👥 Público-Alvo
Investidores que operam exclusivamente Bitcoin, desde iniciantes até avançados.

🧩 Problema a Ser Resolvido
Investidores de Bitcoin têm dificuldade de acompanhar o desempenho real de suas compras após a execução na exchange.
Os históricos das plataformas são confusos e não mostram claramente:
- Lucro atual
- Prejuízo atual
- Evolução da carteira
- Momento ideal para comprar ou vender
O aplicativo deve resolver isso com clareza, simplicidade e inteligência.

🔑 Funcionalidades Principais
1. Registro de Compras
O usuário deve informar:
- Data da compra
- Horário
- Fração de Bitcoin adquirida
- Valor pago em reais
Ao confirmar, o app salva a operação em um histórico ordenado do mais antigo para o mais recente.

2. Cálculo Automático de Lucro/Prejuízo
Assim que a compra é registrada, o app deve:
- Consultar o preço atual do Bitcoin
- Calcular automaticamente o valor atual daquela operação
- Exibir:
- Valor atual da operação (ex.: R$ 220,00)
- Lucro (ex.: R$ 20,00)
- Prejuízo (ex.: R$ 0,00)
- Usar cores:
- Verde para lucro
- Vermelho para prejuízo
O cálculo deve ser feito por operação e também consolidado na carteira.

3. Preço do Bitcoin em Tempo Real
O app deve exibir:
- Cotação atual
- Variação percentual
- Gráfico simples (opcional)
Atualização automática em intervalos curtos.

4. Agente de IA Integrado
O agente deve:
- Resumir o comportamento atual do mercado de criptomoedas
- Informar se o usuário está com lucro ou prejuízo
- Explicar tendências de forma simples e objetiva
- Responder perguntas como:
- “É um bom momento para vender?”
- “O mercado está em alta ou baixa?”
- Sempre em português
- Sempre deixando claro que não é recomendação financeira
O tom deve ser:
- Informativo
- Amigável
- Direto

5. Relatórios Personalizados
O usuário deve conseguir visualizar relatórios por:
- Dia
- Semana
- Mês
- Ano
- Por operação
- Consolidado
Relatórios simples, com gráficos básicos e textos explicativos.

🔐 Requisitos de Segurança
- Login com biometria
- Criptografia local dos dados
- Backup opcional na nuvem

🎨 Requisitos de Interface (UX/UI)
O app deve conter:
- Tela de cadastro de compra
- Tela da carteira com valor total
- Tela de histórico
- Tela do agente IA
- Tela de relatórios
Design minimalista, intuitivo e focado em clareza.

🧠 Comportamento da IA
A IA deve:
- Ser proativa ao explicar o mercado
- Ser clara ao mostrar lucro/prejuízo
- Ser cautelosa ao responder sobre compra/venda
- Evitar termos técnicos complexos
- Ser sempre objetiva

✔️ Fim do Prompt
"

IMAGENS DO APLICATIVO/SITE

<img width="1313" height="986" alt="image" src="https://github.com/user-attachments/assets/bf26a44b-dcdc-4ec2-af88-9966057a6cdb" />
<img width="1303" height="987" alt="image" src="https://github.com/user-attachments/assets/7f8c194a-f31c-4cde-9ef3-6a30b33f0e54" />
<img width="1314" height="996" alt="image" src="https://github.com/user-attachments/assets/405dab0f-4b6a-46da-b600-55aafe90198f" />
<img width="1312" height="1001" alt="image" src="https://github.com/user-attachments/assets/39963462-4725-464f-8ce9-8db4e43cb36e" />
<img width="1311" height="1001" alt="image" src="https://github.com/user-attachments/assets/1fbb9895-c438-4832-a9e7-962088b33131" />
<img width="1312" height="1010" alt="image" src="https://github.com/user-attachments/assets/e9aa69b9-2861-4de4-9235-1bfa56a6bfcc" />
<img width="1314" height="1002" alt="image" src="https://github.com/user-attachments/assets/d8617076-30ad-4da7-b6ce-c5b6a39d9fd3" />

BREVE RELATO

Eu começei a investir por conta própria em Bitcoin, aprendi tudo assistindo vídeos e lendo sites e artigos. Porém, eu tinha muita dificuldade em manusear a exchange, depois ouvi relato de outros investidores também, reclamando da mesma coisa, que comprar era fácil, mas acompanhar era complicado. Por isso pensei nesse aplicativo como resolução. Inicialmente Bitcoin, mas quem sabe, não possa se estender para outras criptos?

REFLEXÃO

Amei todo o processo desse curso, desde às aulas, até esse desafio final. Já impactou a minha vida, pois já consegui desenvolver um site offiline para o meu trabalho e que ajudou a minha chefe, ela ficou feliz e vai me dar uma gratificação.

SOBRE O APLICATIVO CRIADO

Superou as minhas expectativas, tem muito o que melhorar, como por exemplo, um botão de exclusão de compra, mas faltou crédito. Mas de modo geral, cumpriu o prometido.





