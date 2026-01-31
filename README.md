🎾 Sun7 Arena - Experiência de Agendamento e Pagamento
Este projeto foca na otimização da jornada do usuário para o aluguel de quadras e compra de Day Use em uma arena esportiva. O objetivo principal foi criar um fluxo intuitivo, rápido e focado na conversão, direcionando o cliente desde a escolha do serviço até a confirmação do pagamento com o mínimo de atrito.

🚀 O Desafio
O foco central não foi construir um aplicativo completo, mas sim aperfeiçoar a experiência de direcionamento. O projeto prioriza a facilidade com que um atleta pode selecionar um horário e finalizar o pagamento, garantindo que a interface seja um facilitador, e não um obstáculo.

🛠️ O que foi implementado
1. Fluxo de Seleção e Agendamento
Interface Intuitiva: Telas limpas que destacam o resumo da reserva (Arena, horários e valor total).

Dualidade de Serviço: Estrutura preparada para suportar tanto o aluguel de quadras por hora quanto o formato Day Use.

2. Gestão de Variantes e Estados (UI)
Seleção Dinâmica: Implementação de componentes inteligentes para as formas de pagamento (Pix e Cartão).

Feedback Visual: Ao selecionar o método de pagamento, o botão altera seu estado visual (cor dourada e ícone preenchido) de forma instantânea e suave, utilizando Smart Animate.

3. Animação de Microinterações (UX)
Para tornar o processo de pagamento mais realista e seguro para o usuário, foram criados estados de validação:

Estado de Carregamento (Spinner): Um overlay de processamento que simula a comunicação com a operadora do cartão por 1.5 segundos.

Confirmação de Sucesso: Transição automática para um ícone de "Check" animado, fornecendo o reforço positivo de que a reserva foi concluída.

🎨 Protótipo e Design
O projeto foi desenvolvido inteiramente no Figma, utilizando conceitos avançados de:

- Wireframing: Planejamento da arquitetura da informação.
- Mockups de Alta Fidelidade: Design visual seguindo a identidade dark/gold da Sun7 Arena.
- Prototipagem Interativa: Uso de Overlays, After Delay e Change To para simular o comportamento real do app.

📁 Como visualizar
Arquivo Original: O arquivo .fig e as imagens estão disponíveis neste repositório para inspeção de camadas e componentes.

Link do Figma: (https://www.figma.com/proto/F11AoRSyjM3REWPA7BhiQB/Sun7-Arena?node-id=14-275&t=99FvzsyMctoKFQgV-0&scaling=scale-down&content-scaling=fixed&page-id=0%3A1)

![Home Sun7 Arena](prototipo%202/home.png)

🧑‍💻 Autor
Desenvolvido por Rafael Menezes de Santana como parte do estudo de interfaces centradas no usuário para o setor esportivo.
