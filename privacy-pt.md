---
layout: default
title: Política de Privacidade
permalink: /privacy-pt/
---

# MedTime (İlaçVakti) — Política de Privacidade

**Última atualização:** 6 de outubro de 2026

O MedTime (İlaçVakti) é um aplicativo móvel desenvolvido pelo Farmacêutico **Mehmet Tuğberk Özsoy**, projetado para ajudar os usuários a controlar seus medicamentos. Sua privacidade é nossa prioridade máxima; esta política explica de forma transparente quais dados são tratados e como.

Outros idiomas: [English](/ilacvakti-legal/privacy-en/) · [Türkçe](/ilacvakti-legal/privacy-tr/)

---

## 1. Dados Não Coletados

O MedTime **não** coleta identificadores pessoais (nome, e-mail, telefone, número de identidade, data de nascimento, etc.) dos usuários, não os envia aos nossos servidores e não os compartilha com terceiros. Não é necessário criar conta; o aplicativo funciona inteiramente de forma **anônima**.

Lista detalhada dos dados não coletados:
- ❌ Redes de publicidade, criação de perfis ou rastreamento entre aplicativos (para a medição de anúncios na App Store, consulte a Seção 5)
- ❌ Serviços de análise de terceiros (Google Analytics, Facebook Pixel, etc.)
- ❌ Dados de localização
- ❌ Contatos, calendário
- ❌ Armazenamento de gravações de áudio (o microfone só é ativado para a entrada por voz opcional, ver 3.6)
- ❌ Criação de conta, e-mail, telefone
- ❌ Os dados do Apple Saúde **não saem** do seu aparelho (a sincronização opcional de leitura/escrita funciona no aparelho, veja 3.5)
- ❌ Seu backup no iCloud e os dados do compartilhamento familiar **não chegam** ao desenvolvedor (ficam nas suas próprias contas do iCloud, veja 2.1 e 2.2)

---

## 2. Armazenamento Local (Dados Mantidos no Seu Dispositivo)

As informações que você insere são armazenadas **na memória interna do seu dispositivo**; o desenvolvedor não tem nenhum servidor que guarde esses dados:

- Nomes de medicamentos, dosagens, horários de lembrete
- Nomes de perfil (nomes que você fornece) e foto de perfil opcional
- Informações de estoque de medicamentos e fotos
- Histórico de tratamento, registros de doses tomadas/ignoradas
- Dados de sequência (streak) e conquistas (badges)
- Relatórios e anotações de saúde adicionados manualmente
- Preferências de tema, idioma, som de notificação e configurações

Quando você exclui o aplicativo, esses dados são apagados do seu dispositivo. Se o backup no iCloud estiver ativado, seu backup continua na sua própria conta do iCloud (veja 2.1).

### 2.1 Backup no iCloud (ativado por padrão, pode ser desativado)

Se você tiver uma sessão do iCloud no iPhone, o aplicativo salva uma vez por dia um backup dos seus dados na **área privada da sua própria conta do iCloud** (banco de dados privado do Apple CloudKit). Assim, seus remédios e seu histórico voltam quando você troca de telefone ou reinstala o aplicativo.

- O backup inclui remédios, perfis, relatórios, medições, histórico de doses, conquistas/sequências e ajustes do aplicativo. **As fotos não são incluídas.** As medições importadas do Apple Saúde também não; o Apple Saúde as guarda por conta própria e o aplicativo as lê de novo em um telefone novo.
- O backup fica nos campos com criptografia de ponta a ponta da Apple (valores criptografados do CloudKit); a chave fica no seu Porta-chaves do iCloud. Backups muito grandes (anos de histórico) ficam como um arquivo criptografado no iCloud; com a Proteção Avançada de Dados ativada, esse arquivo também tem criptografia de ponta a ponta.
- O backup nunca vai para os servidores do desenvolvedor; **o desenvolvedor não pode acessá-lo.** Ele usa o seu armazenamento do iCloud.
- A lista das suas conexões familiares (quem você acompanha, quem vê suas doses) é salva da mesma forma, para que as conexões não se percam em um novo telefone.
- Para desativar: no aplicativo, aba Perfil › Gerenciamento de dados › Backup no iCloud. Para apagar: Ajustes do iPhone › [seu nome] › iCloud › Gerenciar Armazenamento da Conta › MedTime.

### 2.2 Compartilhamento familiar (opcional)

Você pode acompanhar os remédios de alguém próximo pelo seu próprio telefone. O compartilhamento só começa com **uma ação explícita dos dois lados**: quem vai acompanhar envia um link de convite; a pessoa acompanhada vê no próprio telefone o que será compartilhado e **toca em "Aceitar".**

- **Compartilhado:** os dados das fichas de remédios do perfil compartilhado (como nome, princípio ativo, dose, horários, instruções e nota do remédio), as doses tomadas ou desfeitas e quando foram marcadas, o nome e a cor do perfil e o fuso horário do aparelho.
- **Não compartilhado:** o Diário de medicação (como se sente/efeitos colaterais), medições de pressão e glicemia, fotos, bulas e outros perfis.
- Os dados são transferidos pelo Apple iCloud (compartilhamento do CloudKit) e ficam **na conta do iCloud de quem acompanha**; os nomes e dados dos remédios ficam em campos com criptografia de ponta a ponta. Se uma dose não for marcada no tempo escolhido, quem acompanha recebe um alerta; esse cálculo é feito no aparelho dessa pessoa.
- **O desenvolvedor não pode acessar esses dados**; eles não passam pelos servidores do desenvolvedor.
- **Para parar:** a pessoa acompanhada pode parar quando quiser no cartão "Sua família" da aba Perfil ("… vê suas doses"), e quem acompanha em "Parar de acompanhar" na tela da pessoa. Ao parar, os dados compartilhados são apagados da conta do iCloud de quem acompanha.
- Aceitar um convite é grátis; acompanhar é um recurso Premium (com o Compartilhamento Familiar da Apple, basta a assinatura de um membro da família).

---

## 3. Permissões

### 3.1 Notificações
A permissão de notificação é solicitada para lembretes de medicamentos. As notificações são agendadas **localmente no seu dispositivo**; nenhuma conexão com servidor está envolvida.

### 3.2 Câmera
O acesso à câmera é solicitado apenas na tela *"Adicionar Medicamento"*, para escanear códigos de barras/QR nas caixas de medicamentos ou para fotografar o medicamento. As imagens da câmera não são enviadas a um servidor.

### 3.3 Fotos
O acesso à biblioteca de fotos é solicitado de forma opcional, caso você queira adicionar fotos de medicamentos ou de perfil. As fotos selecionadas são copiadas apenas para a pasta interna do aplicativo no seu dispositivo.

### 3.4 Consulta ao Banco de Dados de Medicamentos
Ao escanear o código de barras/QR na caixa de um medicamento ou pesquisar um medicamento pelo nome, apenas esse **código de barras/código do produto ou o nome do medicamento** é enviado a um serviço oficial de banco de dados de medicamentos para obter o nome e os detalhes do medicamento (bula, embalagem, data de validade, etc.). O serviço utilizado depende da região do seu dispositivo: **NosyAPI** (Turquia), o banco de dados **U.S. FDA openFDA** (Estados Unidos) ou **AEMPS CIMA** (Espanha). Nenhuma informação pessoal (seu nome, dados de perfil, dados de saúde, fotos ou imagens da câmera) é incluída nessa consulta — apenas o código escaneado ou o termo de pesquisa é transmitido. Este recurso é opcional; se você não o utilizar, nenhum dado é enviado.

Você pode revogar as permissões a qualquer momento em iOS *Ajustes &gt; MedTime*.

### 3.5 Apple Saúde (HealthKit) — Sincronização opcional
Usuários Premium podem ativar a sincronização *Ajustes → Apple Saúde*. Quando ativa: (1) as medições de **pressão arterial, glicemia e pulso** inseridas no app e as **doses de insulina** que você marca são **gravadas** no Apple Saúde; (2) as medições de **pressão arterial, glicemia e pulso** que seu medidor, glicosímetro ou outros apps gravam no Apple Saúde são **lidas** no seu diário de medições do app. Este recurso é **totalmente opcional** e vem **desativado por padrão**.

- As permissões de leitura e escrita são aprovadas **separadamente** e de forma explícita pela tela de permissão do iOS; somente os tipos de dados acima são acessados (listas de medicamentos, passos, sono etc. **não são lidos**).
- Apenas medições do **seu próprio perfil** são gravadas; perfis de familiares nunca são sincronizados.
- Os dados vão diretamente para o armazenamento do Saúde no seu aparelho; **nada é enviado a servidores**. Seus dados do Saúde são criptografados pela Apple.
- Se você excluir ou editar uma medição no app, a cópia gravada no Saúde é atualizada/removida.
- Você pode revogar o acesso a qualquer momento em iOS *Ajustes → Saúde → Acesso a Dados e Dispositivos → İlaçVakti*.
- Dados de saúde nunca são usados para publicidade, marketing ou análises (conforme a Diretriz 5.1.3 da App Store).

### 3.6 Microfone e reconhecimento de fala — Opcional
Ao tocar no ícone do microfone na tela de medições, você pode inserir sua pressão ou glicemia **falando**. Este recurso é **totalmente opcional**; o microfone nunca é ativado se você não tocar nesse ícone.

- Sua fala é transcrita **no seu dispositivo**; o aplicativo **exige** o reconhecimento de fala no próprio dispositivo do iOS. **Nenhum áudio é enviado a qualquer servidor** — o recurso funciona também em modo avião.
- **Nenhuma gravação de áudio é mantida.** Depois que a fala é transcrita, os dados de áudio não são armazenados; apenas os números reconhecidos são escritos nos campos da tela.
- O valor reconhecido **não é salvo diretamente**: ele é escrito no campo e só é registrado quando você o confere e toca em **Salvar**.
- O microfone fica ativo apenas nesta tela e somente quando você o inicia; não há escuta em segundo plano.
- Você pode revogar a permissão a qualquer momento em iOS *Ajustes &gt; MedTime*.

---

## 4. Relatórios de Falhas (Sentry)

Para melhorar a estabilidade do aplicativo, relatórios anônimos de falhas são coletados por meio do serviço **Sentry**.

**Coletado:**
- Data e hora da falha, modelo do dispositivo, versão do iOS, versão do aplicativo
- Mensagem de erro e rastreamento técnico de pilha (stack trace)
- Contexto técnico anterior à falha (por exemplo, telas abertas)

**Não coletado:**
- Nome de usuário, e-mail, endereço IP (`sendDefaultPii` desativado)
- Capturas de tela, dados pessoais de medicamentos, dados de saúde
- Fotos ou conteúdo de relatórios

Os dados do Sentry são usados exclusivamente para a melhoria do aplicativo; **nunca** para marketing ou publicidade. Os dados do Sentry são retidos por até **90 dias**.

Política de privacidade do Sentry: <https://sentry.io/privacy/>

---

## 5. Assinatura Premium e RevenueCat

O MedTime oferece uma **assinatura Premium** opcional:

| Plano | Preço | Recursos |
|---|---|---|
| Mensal | 3,99 € | Renovação automática |
| Anual | 29,99 € | Inclui **teste gratuito de 7 dias**, renovação automática |
| Vitalício | 49,99 € | **Pagamento único** — não é uma assinatura e não é renovado |

> Os valores acima referem-se à App Store de Portugal. **Os preços variam conforme o país** — no Brasil, por exemplo, são R$ 6,90 / R$ 39,90 / R$ 129,90. A App Store mostra o valor exato na sua moeda local antes de concluir a compra.

### Gerenciamento da Assinatura
- As assinaturas se renovam automaticamente; a cobrança é feita na sua conta do iTunes caso não seja cancelada com pelo menos **24 horas** de antecedência em relação ao fim do período atual.
- Cancelamento: iOS *Ajustes → Apple ID → Assinaturas*.
- O **Compartilhamento Familiar** está habilitado — uma assinatura pode ser compartilhada com até 5 membros da família.
- Os pagamentos são processados pela Apple; o MedTime não tem acesso às informações do cartão.

### Acesso Gratuito Vitalício para Usuários Anteriores
Os usuários que instalaram a versão **2.0.1 (build 5) ou anterior** recebem automaticamente acesso **Premium gratuito vitalício**. Isso é verificado de forma anônima no dispositivo usando o campo `originalApplicationVersion` do recibo da Apple.

### RevenueCat (Validação da Assinatura)
O serviço **RevenueCat** é usado para validar o estado da assinatura. Um identificador anônimo (App User ID) derivado do seu Apple ID e os dados do recibo da Apple são enviados ao RevenueCat. Seu nome, e-mail ou informações de contato **não são compartilhados**.

Política de privacidade do RevenueCat: <https://www.revenuecat.com/privacy/>

### Medição de Publicidade (Apple Search Ads)
O MedTime veicula ocasionalmente anúncios na App Store. Para medir qual anúncio trouxe você até o aplicativo, um *token de atribuição* gerado pela Apple **no momento da instalação** é enviado ao RevenueCat, que consulta a Apple para saber se a instalação veio de um anúncio.

- O token **não é o seu identificador de publicidade (IDFA)** e não identifica você nem o seu dispositivo. Por isso a tela de *Transparência de Rastreamento de Apps* do iOS não é exibida — não há rastreamento entre aplicativos.
- A Apple devolve apenas informações **em nível de campanha**. Essas informações **não são vinculadas** ao seu nome, ao seu perfil, aos seus medicamentos ou aos seus dados de saúde.
- A operação ocorre **uma única vez, na instalação**; depois disso o seu uso do aplicativo não é rastreado para fins publicitários.
- A única finalidade é verificar se o orçamento de publicidade está sendo bem empregado; **não** é usada para direcionar anúncios a você nem para vender dados.

### Termos de Uso
Aplica-se o EULA Padrão da Apple: <https://www.apple.com/legal/internet-services/itunes/dev/stdeula/>

---

## 6. Compartilhamento de Dados

O MedTime **não compartilha os dados dos usuários com terceiros, não os vende e não os utiliza para fins de marketing**. As únicas exceções são:

- As consultas ao banco de dados de medicamentos descritas na Seção 3.4 (NosyAPI / U.S. FDA openFDA / AEMPS CIMA) — apenas o código escaneado ou o nome do medicamento pesquisado é transmitido; não contém nenhum dado pessoal.
- Os relatórios anônimos de falhas descritos na Seção 4 (Sentry).
- Os dados anônimos de validação de assinatura e o token de atribuição de publicidade sem identificação descritos na Seção 5 (RevenueCat + Apple).
- O compartilhamento familiar descrito na Seção 2.2, **iniciado e aprovado por você** — apenas com a pessoa que você convidou ou cujo convite você aceitou, pelo Apple iCloud.

---

## 7. Seus Direitos sob o GDPR (Usuários da UE)

Se você reside na UE, sob o Regulamento Geral sobre a Proteção de Dados (GDPR) você tem o direito de **acessar, corrigir, excluir, opor-se ao tratamento e à portabilidade dos dados**. Nossas bases legais são: necessidade para a prestação do serviço (Artigo 6(1)(b)) e interesse legítimo para o relato de erros (Artigo 6(1)(f)).

---

## 8. Seus Direitos sob a KVKK Turca

Sob a Lei Turca de Proteção de Dados Pessoais (KVKK), Artigo 11, você tem direitos que incluem: saber se seus dados são tratados, solicitar informações, solicitar correção ou exclusão, conhecer os terceiros para os quais os dados foram transferidos, opor-se a resultados de tratamento automatizado e pleitear indenização. Para exercer esses direitos, entre em contato pelo e-mail <ilacvaktidestek@gmail.com>. As solicitações são respondidas em até **30 dias**.

---

## 9. Privacidade das Crianças

O aplicativo é classificado como **4+**. Não coletamos dados de crianças menores de 13 anos de forma consciente. Se um responsável usar o aplicativo para adicionar o perfil de uma criança (membro da família), os dados do perfil permanecem armazenados apenas localmente no dispositivo.

---

## 10. Segurança dos Dados

Como seus dados são armazenados majoritariamente no seu dispositivo, eles são protegidos pela criptografia de hardware do iOS (Secure Enclave). A comunicação com serviços de terceiros é criptografada por HTTPS. Os dados de remédios do backup no iCloud e do compartilhamento familiar ficam em campos com criptografia de ponta a ponta do Apple CloudKit; ninguém, nem o desenvolvedor, consegue lê-los.

---

## 11. Alterações nesta Política

Podemos atualizar esta política periodicamente. Alterações significativas serão anunciadas por meio de notificação no aplicativo ou das notas de versão. Por favor, consulte regularmente a data de *Última atualização*.

---

## 12. Contato

E-mail: <ilacvaktidestek@gmail.com>
