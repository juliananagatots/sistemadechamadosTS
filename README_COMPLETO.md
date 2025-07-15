
# 📌 Trade Stars | Sistema Interno de Chamados

Sistema interno web para abertura, acompanhamento e gestão de chamados técnicos entre os departamentos de suporte e desenvolvimento da Trade Stars. Desenvolvido com HTML, CSS, JavaScript, integração com Supabase e armazenamento de imagens via Google Drive.

---

## 🧱 Tecnologias Utilizadas

- **HTML5 & CSS3**: Estrutura da interface e estilização responsiva
- **JavaScript (Vanilla)**: Lógica de interação e manipulação de dados
- **Supabase**: Backend-as-a-service (auth, banco de dados, storage)
- **Chart.js**: Visualização gráfica de métricas e KPIs
- **Font Awesome**: Ícones para navegação e ações
- **Google Drive API** (via upload script): Armazenamento de imagens e anexos

---

## ⚙️ Funcionalidades

### 🎫 Gestão de Chamados
- Abertura de chamados por categoria:
  - Problemas com alunos
  - Problemas na plataforma
  - Eventos e mentorias
  - Atualização de cadastro
- Edição e visualização completa dos detalhes de chamados
- Visualização de anexos com suporte a zoom
- Filtros avançados por status, prioridade, produto, departamento e busca geral

### 🧮 Dashboard de Métricas (para Devs)
- Chamados abertos no dia
- Chamados pendentes e resolvidos (7 dias)
- Tempo médio de resolução
- Taxa de resolução
- Gráficos: Distribuição por status e prioridade

### 🧑‍💻 Comunicação Interna
- Chat em tempo real por chamado entre devs e suporte
- Histórico de interações
- Diferenciação visual entre autor (suporte/dev)

### 📢 Avisos Internos
- Criação, edição e arquivamento de avisos
- Fixação de avisos no topo
- Cores personalizadas por aviso
- Indicador visual de novo aviso (ícone de sininho)

### 🧷 Anexos
- Upload de imagens para chamados
- Visualização em miniaturas e zoom no clique
- Exclusão e destaque de anexos

### 🧩 Atualização Cadastral
- Busca de aluno por e-mail original
- Exibição comparativa dos dados antigos e novos
- Cadastro direto de aluno, caso não encontrado

---

## 🗂 Estrutura do Projeto

```
📁 trade-stars-chamados/
├── index.html             # Página principal com HTML, CSS e JS integrados
├── README.md              # Este documento
├── /assets/               # (opcional) Imagens e ícones customizados
└── /uploads/              # (opcional) Armazenamento local de anexos
```

---

## 🔐 Supabase (Configuração)

1. Crie seu projeto em [https://supabase.com](https://supabase.com)
2. Configure as seguintes tabelas:
   - `chamados`: para os dados dos chamados
   - `usuarios`: suporte e devs
   - `avisos`: gerenciamento de anúncios
   - `anexos`: links de arquivos dos chamados
3. Integre a biblioteca Supabase no HTML:
```html
<script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2"></script>
```

4. Configure sua instância no JavaScript:
```js
const supabase = createClient('https://SEU-PROJETO.supabase.co', 'public-anon-key');
```

---

## 🚀 Como Executar Localmente

```bash
git clone https://github.com/seu-usuario/trade-stars-chamados.git
cd trade-stars-chamados
# abra o index.html com o navegador ou use um servidor local:
live-server .
```

---

## 📸 Capturas de Tela

> Adicione imagens demonstrando:
> - Tela de abertura de chamados
> - Dashboard com gráficos
> - Seção de avisos
> - Visualização de um chamado com anexos e chat

---

## ✨ Melhorias Futuras

- [ ] Notificações por e-mail/SMS
- [ ] Login unificado com o ambiente corporativo (SSO)
- [ ] Exportação de relatórios em PDF
- [ ] Comentários em linha nos chamados
- [ ] Controle de SLA por departamento

---

## 🙋‍♀️ Desenvolvido por

**Juliana**  
TI & Suporte — Trade Stars  
📧 [email@email.com] | 🌐 [linkedin.com/in/seuusuario]

---

## 📄 Licença

Este projeto é de uso interno da Trade Stars.  
Distribuição ou comercialização não autorizada é proibida.

