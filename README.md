
trabalho sobre o GitHub e sua relação com o pipeline de feedback da Aula 2, abordando DevOps, testes automatizados e feedback contínuo.

![Capa do trabalho](./capa.jpg)

# Trabalho: GitHub e Pipeline de Feedback

**Componente curricular:** Desenvolvimento de Sistemas  
**Conteúdo:** Semana 21 — Aula 2: Pipeline de Feedback  
**Tema:** Cultura DevOps e Feedback Contínuo

## 1. Introdução

O GitHub é uma plataforma utilizada para armazenar projetos, organizar arquivos e acompanhar as alterações realizadas no código-fonte. Ele utiliza o Git, um sistema de controle de versão que permite registrar modificações e acompanhar o histórico de um projeto.

Além disso, o GitHub facilita o trabalho em equipe, permitindo que diferentes desenvolvedores compartilhem códigos, contribuam para um mesmo projeto e revisem alterações.

Sua utilização também pode estar relacionada à automação de tarefas e às práticas de DevOps, que buscam melhorar a colaboração, a agilidade e a qualidade no desenvolvimento de softwares.

Neste trabalho, será apresentada a relação entre o GitHub e o Pipeline de Feedback, destacando a importância da automação, dos testes e da identificação rápida de falhas.

## 2. O que é um Pipeline de Feedback?

O Pipeline de Feedback é uma sequência automática de etapas que valida o código a cada alteração realizada.

Seu objetivo principal é identificar falhas o mais rápido possível, permitindo que os desenvolvedores recebam informações sobre os resultados das verificações e realizem as correções necessárias.

De acordo com a Aula 2 da Semana 21, o fluxo básico é:

**Código → Build → Teste → Resultado**

Esse processo está relacionado à cultura DevOps, que incentiva a colaboração, a automação e a melhoria contínua durante o desenvolvimento de softwares.

## 3. Etapas do Pipeline de Feedback

O pipeline apresentado na aula possui três etapas principais:

- **Build:** prepara e compila o código, quando necessário, verificando se ele foi construído corretamente.
- **Test:** executa testes automatizados, como testes unitários e de integração, para verificar se o código funciona conforme o esperado.
- **Monitor:** acompanha os resultados e utiliza alertas automáticos para informar a equipe sobre possíveis falhas.

Essas etapas ajudam os desenvolvedores a identificar problemas rapidamente e a evitar que códigos com falhas avancem para as próximas etapas do processo.

Ferramentas como GitHub Actions e Jenkins podem automatizar essas verificações e apresentar os resultados da execução.

## 4. Como o GitHub se relaciona com o Pipeline de Feedback?

O GitHub permite armazenar o código-fonte, controlar suas versões e acompanhar as alterações realizadas em um projeto.

Por meio do GitHub Actions, é possível configurar fluxos de trabalho automatizados que executam tarefas após determinados eventos, como o envio de alterações ao repositório.

Por exemplo, quando um desenvolvedor envia uma modificação no código, um fluxo configurado pode executar testes automaticamente e apresentar os resultados.

Se uma verificação falhar, a equipe poderá analisar o problema e corrigir o código. Se as verificações forem concluídas com sucesso, o resultado também poderá ser visualizado no GitHub.

Dessa forma, o GitHub pode contribuir para o Pipeline de Feedback, facilitando a automação, o acompanhamento das alterações e a identificação de erros.

É importante destacar que essas verificações precisam ser configuradas para funcionar automaticamente.

## 5. A relação entre DevOps e Feedback Contínuo

DevOps é uma abordagem que busca aproximar as equipes de desenvolvimento e de operações, incentivando a colaboração e a automação dos processos.

O feedback contínuo permite que os desenvolvedores recebam informações frequentes sobre o resultado das alterações realizadas no código.

Quando essas práticas são utilizadas em conjunto, a equipe consegue identificar falhas mais cedo, reduzir o retrabalho e melhorar a qualidade das entregas.

Assim, o Pipeline de Feedback contribui para um processo de desenvolvimento mais ágil, organizado e eficiente.

## 6. Integração Contínua e Testes Automatizados

A integração contínua, conhecida como CI (Continuous Integration), é uma prática que envolve integrar alterações no código frequentemente e verificar se elas funcionam corretamente.

Essas verificações podem incluir a construção do projeto e a execução de testes automatizados.

Os testes automatizados são executados por ferramentas para verificar se determinadas partes do software funcionam conforme o esperado.

No GitHub, o GitHub Actions pode ser configurado para executar esses testes automaticamente após determinadas alterações.

Dessa maneira, a equipe recebe feedback sobre possíveis falhas e pode corrigi-las antes que avancem no processo de desenvolvimento.

## 7. Mentalidade Fail Fast

A mentalidade Fail Fast significa descobrir as falhas o mais cedo possível.

Essa abordagem é importante porque um erro identificado rapidamente tende a ser mais simples de investigar e corrigir do que um problema descoberto muito tempo depois.

Por exemplo, se uma alteração no código causar uma falha em um teste automatizado, o pipeline poderá informar o problema logo após a execução da verificação.

Assim, o desenvolvedor poderá corrigir o erro antes de continuar com as próximas etapas.

O objetivo é reduzir o impacto das falhas, evitar retrabalho e melhorar a qualidade do software.

## 8. Feedback Rápido e Lead Time

Lead time é o tempo que uma ideia leva desde o início do processo de desenvolvimento até estar disponível em produção.

A integração contínua e a automação podem ajudar a reduzir esse tempo, tornando as verificações mais rápidas e facilitando a identificação de problemas.

Quanto mais tarde uma falha é descoberta, maior pode ser o custo e a complexidade de sua correção.

Por isso, o feedback rápido é importante para melhorar o fluxo de desenvolvimento e permitir entregas mais seguras e eficientes.

## 9. Exemplo Prático de um Pipeline de Feedback

Imagine que três desenvolvedores estejam trabalhando juntos em um projeto armazenado no GitHub.

Um dos integrantes realiza uma alteração no código e envia a modificação para o repositório.

O processo pode acontecer da seguinte maneira:

1. **Código:** o desenvolvedor realiza uma alteração no projeto.
2. **Build:** o pipeline prepara e verifica a construção do código.
3. **Test:** os testes automatizados são executados para verificar o funcionamento do código.
4. **Resultado:** o sistema apresenta se as verificações foram concluídas com sucesso ou se foram encontradas falhas.
5. **Correção:** caso ocorra um erro, o desenvolvedor analisa o resultado e realiza os ajustes necessários.
6. **Nova verificação:** após a correção, as etapas podem ser executadas novamente.

Esse exemplo demonstra como o GitHub Actions pode ser utilizado para automatizar verificações e como o Pipeline de Feedback ajuda a equipe a receber informações rapidamente.

## 10. Benefícios do Pipeline de Feedback

A utilização de um Pipeline de Feedback pode oferecer diversos benefícios:

- **Identificação rápida de erros:** permite descobrir falhas durante o desenvolvimento.
- **Redução do retrabalho:** facilita a correção de problemas antes que eles se tornem mais complexos.
- **Melhoria da qualidade:** ajuda a verificar se o código atende aos critérios definidos.
- **Maior agilidade:** automatiza tarefas e acelera as verificações.
- **Colaboração:** facilita o compartilhamento dos resultados entre os integrantes da equipe.
- **Mais organização:** permite acompanhar as alterações e os resultados das verificações.
- **Entregas mais seguras:** ajuda a identificar problemas antes que o software seja disponibilizado em produção.

Esses benefícios contribuem para a melhoria contínua e para um processo de desenvolvimento mais eficiente.

## 11. Conclusão

Conclui-se que o GitHub e o Pipeline de Feedback podem trabalhar juntos para tornar o desenvolvimento de softwares mais organizado, ágil e eficiente.

Enquanto o GitHub permite armazenar projetos, controlar versões e colaborar com outros desenvolvedores, ferramentas como o GitHub Actions possibilitam automatizar tarefas e executar verificações no código.

As etapas Build, Test e Monitor ajudam a acompanhar os resultados e identificar falhas rapidamente. Além disso, a mentalidade Fail Fast e a redução do Lead Time reforçam a importância de receber feedback em pouco tempo.

Portanto, a utilização dessas práticas contribui para reduzir o retrabalho, melhorar a qualidade do software e tornar as entregas mais seguras.

## 12. Referências

- GITHUB. Documentação oficial. Disponível em: https://docs.github.com/pt
- GITHUB. GitHub Actions. Disponível em: https://docs.github.com/pt/actions
- AMAZON WEB SERVICES (AWS). O que é um pipeline de CI/CD? Disponível em: https://aws.amazon.com/pt/what-is/ci-cd-pipeline/
- Material didático da Secretaria da Educação do Estado de São Paulo. Semana 21, Aula 2: Pipeline de Feedback. Código da aula: SISANO1C3B4S21A2
