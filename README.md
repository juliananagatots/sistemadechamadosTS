
# 📌 Trade Stars | Sistema Interno de Chamados

Sistema interno de abertura e gerenciamento de chamados entre os setores de suporte e desenvolvimento, com integração ao Supabase e interface interativa em HTML/CSS/JavaScript.

---

## 🧱 Tecnologias Utilizadas

- **HTML5/CSS3**: Estrutura e estilização responsiva  
- **JavaScript Vanilla**  
- **Supabase**: Backend como serviço (autenticação, banco de dados e storage)  
- **Chart.js**: Exibição de gráficos dinâmicos  
- **Font Awesome**: Ícones e UI  
- **Google Drive (integrado)**: Para armazenamento de anexos  

---

## 🔧 Funcionalidades

- **📁 Abertura de chamados** por diferentes categorias: 
  - Problemas com alunos
  - Problemas de plataforma
  - Eventos/mentorias
  - Atualização cadastral

- **📊 Painel de métricas** (visível apenas para devs):
  - Chamados por status e prioridade
  - Tempo médio de resolução
  - Taxa de resolução semanal

- **📌 Seção de avisos**:
  - Avisos fixos e arquivados
  - Cores personalizadas
  - Notificações por sininho

- **🧾 Filtro e pesquisa de chamados**:
  - Por status, prioridade, produto, departamento ou termo livre

- **📬 Sistema de comunicação interno (chat)** entre suporte e dev dentro do chamado

- **📎 Upload de imagens como anexo**, com visualização em galeria e zoom

- **🎨 Interface responsiva e moderna** com dark theme e animações interativas

---

## 🗂 Estrutura do Projeto

```
├── index.html           # Página principal com todos os módulos HTML/CSS/JS integrados
├── style.css            # Estilos inline incluídos no HTML
├── script.js            # Lógica JavaScript (integrado no final do HTML)
├── /images              # (opcional) pasta para avatares, logos ou ícones customizados
├── README.md            # Documentação (este arquivo)
```

---

## ⚙️ Integração com Supabase

- **Banco de dados**: Chamados, usuários (alunos e suporte), avisos  
- **Autenticação**: Por e-mail  
- **Storage**: Para imagens anexadas nos chamados  

---

## 📝 Como Usar

1. Clone o projeto:
```bash
git clone https://github.com/sua-conta/seu-repo-chamados.git
```

2. Edite as chaves do Supabase no topo do script JavaScript (caso separado):
```js
const supabase = createClient('https://xxxxx.supabase.co', 'public-anon-key');
```

3. (Opcional) Substitua o logo padrão por um personalizado em:
```html
<img class="logo-img" src="sua-logo.png">
```

4. Hospede o sistema em um ambiente web compatível (GitHub Pages, Vercel, Netlify ou seu próprio servidor).

---

## 📌 Melhorias Sugeridas

- ✅ Remoção de login e uso direto por suporte  
- ✅ Cadastro rápido de alunos caso não existam na base  
- ✅ Dashboard com gráficos em tempo real  
- ⏳ Integração com envio de notificações por e-mail (em desenvolvimento)

---

## 📸 Capturas de Tela

*Inclua imagens do sistema em funcionamento aqui para fins de demonstração.*

---

## 👩‍💻 Desenvolvido por

Juliana - TI & Suporte @ Trade Stars  
[LinkedIn | GitHub | Portfólio] (opcional)

