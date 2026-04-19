
# Projeto de Interface

## User Flow

### 1. Fluxo de Adoção (Busca Direta)
*Indicado para o usuário que já possui um perfil de animal em mente.*

1. **Página Inicial (Home):** O usuário utiliza a barra de busca ou clica em "Ver pets disponíveis".
2. **Vitrine de Pets (`/pets-disponiveis`):** Navegação pela grade de animais.
   - Botão **"Adote"**: Atalho direto para o formulário.
   - Botão **"i"**: Acesso aos detalhes completos.
3. **Detalhes do Pet:** Análise de idade, peso, status de saúde e personalidade.
4. **Ação Final:** Clique em **"Quero Adotar o animal!"** para iniciar o processo.

<img width="529" height="448" alt="image" src="https://github.com/user-attachments/assets/d017ccbb-5ecb-4ed5-ac37-d6c70ea42ae9" />

<img width="534" height="452" alt="image" src="https://github.com/user-attachments/assets/3763b01c-04c5-40d0-8d56-255dee0df1d6" />


---

### 2. Fluxo de Descoberta (Match Perfeito)
*Para usuários que buscam uma recomendação baseada em seu estilo de vida.*

* **Entrada:** O usuário seleciona "Fazer quiz" no menu de navegação.
* **Interação (`/quiz`):** Responde a 3 perguntas fundamentais (moradia, convivência e nível de atividade).
* **Processamento (`/resultado-do-quiz`):** A plataforma exibe o pet ideal com a justificativa do "match".
* **Ação Final:** Clique em **"Adote agora!"** para visualizar os animais com aquele perfil.

<img width="538" height="455" alt="image" src="https://github.com/user-attachments/assets/dc36c31f-acde-4269-9d65-23848c00afce" />

<img width="532" height="448" alt="image" src="https://github.com/user-attachments/assets/a2fd9921-8a0b-4280-854d-e8cdc79eea93" />


---

### 3. Fluxo de Doação e Apoio
*Focado em usuários que desejam contribuir com a causa financeiramente ou com serviços.*

1. **Menu:** Seleção da opção "Doar".
2. **Página de Doação (`/DOAÇÃO`):** Visualização do impacto social e escolha do valor.
3. **Ação Final:** Clique em **"Doar agora!"**.
   - *Opções secundárias:* Doação de itens, voluntariado ou compartilhamento.

 <img width="533" height="449" alt="image" src="https://github.com/user-attachments/assets/8e15bb49-2705-48e3-8e24-18ea821f4b65" />

---

### 4. Fluxo de Autenticação (Acesso à Conta)
*Gestão de segurança para usuários comuns e instituições.*

* **Início:** Clique em "Entre ou cadastre-se" no topo do site.
* **Login (`/entrar-no-seu-cadastro`):** Acesso via e-mail e senha.
* **Cadastro (`/cadastrar-na-pagina`):** Fluxo para novos usuários (Nome, E-mail, Telefone e Senha).
* **Ação Final:** Botão **"Criar conta"** para acesso imediato.

  <img width="535" height="450" alt="image" src="https://github.com/user-attachments/assets/ba8b3939-f541-43fd-98d2-4cf8821d50fc" />

  <img width="532" height="451" alt="image" src="https://github.com/user-attachments/assets/09fa1325-c97c-48e8-8749-d455e81151be" />


---

### 5. Fluxo da ONG (Gestão e Cadastro)
*Fluxo administrativo exclusivo para organizações parceiras gerenciarem seus abrigos.*

| Etapa | Página | Funcionalidade |
| :--- | :--- | :--- |
| **Parceria** | `/DOAÇÃO-3` | Informações sobre o programa e adesão. |
| **Cadastro Institucional** | `/DOAÇÃO-4` | Registro de CNPJ, localização e documentação da ONG. |
| **Painel de Controle** | `/DOAÇÃO-7` | Dashboard com métricas: Animais, Adoções e Visualizações. |
| **Gestão de Anúncios** | `/DOAÇÃO-7` | Lista de animais cadastrados com opções de "Editar" ou "Excluir". |
| **Cadastro de Pet** | `/DOAÇÃO-6` | Formulário técnico: Foto, espécie, porte, sexo e descrição. |
| **Visibilidade** | `/DOAÇÃO-5` | Listagem pública na página de "ONGs Parceiras". |

<img width="523" height="452" alt="image" src="https://github.com/user-attachments/assets/607aec8f-e2d8-412b-afc2-2e4cc32d4f64" />

<img width="532" height="449" alt="image" src="https://github.com/user-attachments/assets/1167cd0f-7f0f-4608-9ab1-66bb9873365e" />

<img width="528" height="451" alt="image" src="https://github.com/user-attachments/assets/a3b44486-9dfe-4ae0-83a1-663cf2997604" />


---

> **Links Úteis**:
> - [User Flow: O Quê É e Como Fazer?](https://medium.com/7bits/fluxo-de-usu%C3%A1rio-user-flow-o-que-%C3%A9-como-fazer-79d965872534)
> - [User Flow vs Site Maps](http://designr.com.br/sitemap-e-user-flow-quais-as-diferencas-e-quando-usar-cada-um/)
> - [Top 25 User Flow Tools & Templates for Smooth](https://www.mockplus.com/blog/post/user-flow-tools)


## Wireframes

O objetivo do wireframe do nosso site é facilitar a navegação do usuário e planejar um sistema visualmente atrativo, focado em auxiliar no processo de adoção, contribuindo para aumentar as chances de sucesso.

https://www.figma.com/site/ZOO8VfcLVItzkpR0VXhpHL/Wireframes?node-id=0-1&t=xOOM0zqFEUE5d8xq-1

### Wireframes do site

**Pagina inicial**

Focamos em um layout simples e direto, que chamasse atenção para os pontos principais, como os filtros, a barra de busca e a opção de ver mais pets. A ideia foi facilitar a navegação do usuário, permitindo que ele encontre rapidamente um animal de interesse.
Também pensamos em destacar o botão principal de “ver pets disponíveis”, para guiar o usuário logo no início da navegação. Além disso, organizamos o processo em etapas (encontrar, conhecer, adotar e levar para casa), para deixar mais claro como funciona a adoção.
Outro ponto foi o uso de mensagens com apelo emocional, com o objetivo de engajar mais os usuários e aumentar a probabilidade de adoção. Assim, o sistema tenta ser simples, fácil de usar e ao mesmo tempo mais envolvente.

<img width="529" height="448" alt="image" src="https://github.com/user-attachments/assets/236b86ea-f6bc-4275-b036-07466bbe6194" />

**Menu e Aba de cadastro/entrar**


Também haverá uma área onde os usuários poderão se cadastrar ou entrar no sistema. Nessa parte, o usuário informa dados como nome, e-mail, telefone e senha, permitindo a criação de uma conta.
Essas informações poderão ser disponibilizadas para as ONGs parceiras caso haja interesse em algum animal, facilitando o contato e tornando o processo de adoção mais rápido e organizado.
Além disso, o sistema também conta com a opção de login para usuários já cadastrados, garantindo acesso às funcionalidades de forma mais prática.
O menu lateral apresenta tópicos como início, como funciona, buscar pet, fazer quiz, doar, contato, meus anúncios e ONGs parceiras. Esses tópicos ajudam na navegação, pois redirecionam o usuário diretamente para a área desejada, tornando o uso do site mais simples e objetivo.


<img width="527" height="452" alt="image" src="https://github.com/user-attachments/assets/7042c11c-20db-4756-b101-0b269d0dcccd" />

<img width="535" height="450" alt="image" src="https://github.com/user-attachments/assets/430e8bf4-6374-410c-989d-781414e188cd" />

<img width="532" height="451" alt="image" src="https://github.com/user-attachments/assets/e8c115bb-429e-4edb-9fa4-b3e7f34187af" />

**Pet's disponiveis**


Parte em que o usuário pode ter uma breve noção dos animais disponíveis, podendo analisar qual gostaria de adotar. Os botões, imagens e as informações básicas ajudam a aproximar mais o usuário do animal, gerando maior identificação e, assim, facilitando o processo de adoção e o engajamento com a causa.
Além disso, há uma área clicável onde o usuário pode acessar informações mais detalhadas sobre um pet que tenha despertado interesse.


<img width="534" height="452" alt="image" src="https://github.com/user-attachments/assets/28851285-54d4-474d-b482-772d304de8b5" />

<img width="533" height="460" alt="image" src="https://github.com/user-attachments/assets/b0632a65-b9cf-4541-b30e-1ce91e0d04c1" />

**Quiz**


Criamos essa aba para facilitar a escolha do usuário e ajudar a encontrar um lar adequado para os animais, considerando suas necessidades. Dessa forma, buscamos contribuir para uma escolha mais assertiva e uma melhor adaptação do pet ao novo ambiente.
Nessa área, haverá botões que incentivam a adoção e um questionário básico, que ajudará a direcionar o usuário para a melhor opção de acordo com suas limitações e estilo de vida. Ao final do quiz, será apresentada uma sugestão de animal, junto com uma breve descrição e o motivo pelo qual ele é a melhor alternativa.


<img width="538" height="455" alt="image" src="https://github.com/user-attachments/assets/0531fe15-877b-4ce1-b771-5c7f4ab613a1" />

**Doações**


Essa parte foi criada para engajar a comunidade a contribuir com o funcionamento das ONGs. Nela, os usuários podem doar qualquer valor, contando também com mensagens motivacionais que incentivam a participação na causa.
Além disso, há botões chamativos que buscam atrair a atenção do usuário e incentivar ainda mais a contribuição, junto com depoimentos de outros doadores, o que ajuda a gerar mais confiança.
Também consideramos aqueles que não podem ajudar financeiramente, oferecendo alternativas como compartilhar a causa ou adotar um animal.
O principal objetivo dessa área é aumentar o engajamento com a causa animal e incentivar diferentes formas de contribuição.

<img width="533" height="449" alt="image" src="https://github.com/user-attachments/assets/8b3cc349-8fe7-4a46-9dfe-af2efe2c7668" />

**ONG's cadatradas/ cadastrar sua ONG**


Para gerar maior participação das pessoas, é importante que o público tenha confiança. Por isso, nessa parte apresentamos as ONGs parceiras do site, além de informações como quantidade de animais resgatados, número de voluntários, entre outros dados relevantes.
Os formulários de cadastro das ONGs devem conter, inicialmente, informações básicas da instituição, com o objetivo de aumentar a confiabilidade. Entre esses dados estão: nome, contato, CNPJ, localização, site oficial, entre outros. Ao final, haverá uma seção para envio de documentos essenciais, concluindo o cadastro.
Posteriormente, haverá a etapa em que as instituições poderão cadastrar os animais disponíveis para adoção. Esse processo será semelhante ao cadastro das ONGs, sendo necessário incluir fotos dos animais, informações sobre sua saúde e uma breve descrição.

<img width="528" height="445" alt="image" src="https://github.com/user-attachments/assets/04107020-1570-43d4-b254-314c8ab41e1f" />

<img width="523" height="452" alt="image" src="https://github.com/user-attachments/assets/bdcc5b29-cdc8-4973-a950-a0fa12c54e2b" />

<img width="528" height="451" alt="image" src="https://github.com/user-attachments/assets/60ca7608-bd03-42cc-af1e-dfe9bfa3dd60" />


**ONG's pareceiras**


Nessa parte, o usuário terá acesso a informações básicas sobre as ONGs cadastradas, além dos dados de contato, caso queira falar diretamente com a instituição. Isso permite tirar dúvidas sobre o processo de adoção ou até mesmo agendar uma visita ao local.
Por isso, é importante ter um botão chamativo de “entrar em contato”, facilitando esse acesso. Também são apresentados dados essenciais, como localização, telefone e outras informações relevantes, tornando a comunicação mais rápida e prática.

<img width="534" height="452" alt="image" src="https://github.com/user-attachments/assets/e3f4b48e-8cfe-4fb7-ad10-a33d3c7f7e85" />

**Meus anuncios**


É importante que as ONGs consigam gerenciar os anúncios dos animais de forma prática. Por isso, elas poderão apagar um anúncio quando o pet for adotado, alterar suas informações, visualizar quais ainda estão ativos e acompanhar quantas pessoas visitaram cada pet.
Pensando nisso, será disponibilizada uma aba de fácil acesso e edição, com todas as ferramentas necessárias para agilizar o processo de adoção e aumentar as chances de sucesso.

<img width="532" height="449" alt="image" src="https://github.com/user-attachments/assets/32e8711e-8d5a-4976-9cb4-483d8353bddb" />

**Duvidas e fechamneto do site**


Teremos botões e títulos chamativos para que o usuário que estiver procurando suporte encontre facilmente as informações e consiga resolver suas dúvidas.
Ao final da página, haverá um menu minimalista, onde o usuário pode voltar para outras abas do site que desejar acessar.

<img width="540" height="445" alt="image" src="https://github.com/user-attachments/assets/8f07e93f-37f1-48ac-8eba-1d463b2f38c7" />













 
> **Links Úteis**:
> - [Protótipos vs Wireframes](https://www.nngroup.com/videos/prototypes-vs-wireframes-ux-projects/)
> - [Ferramentas de Wireframes](https://rockcontent.com/blog/wireframes/)
> - [MarvelApp](https://marvelapp.com/developers/documentation/tutorials/)
> - [Figma](https://www.figma.com/)
> - [Adobe XD](https://www.adobe.com/br/products/xd.html#scroll)
> - [Axure](https://www.axure.com/edu) (Licença Educacional)
> - [InvisionApp](https://www.invisionapp.com/) (Licença Educacional)
