# 🎓 ScribMeMind - Corretor Profissional de Redações ENEM

![Status](https://img.shields.io/badge/status-ativo-success)
![Version](https://img.shields.io/badge/version-2.1-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![ENEM](https://img.shields.io/badge/ENEM-Nota%201000-orange)

Um sistema completo e profissional para geração, análise e correção de redações para o ENEM, utilizando inteligência artificial para criar textos únicos, estruturados e com potencial para nota máxima.

## ✨ Demonstração

![Interface do Gerador de Redações](https://via.placeholder.com/800x400?text=ScribMeMind+-+Corrector+de+Reda%C3%A7%C3%B5es+ENEM)

## 📋 Sobre o Projeto

ScribMeMind é uma aplicação web completa que utiliza a API do Google Gemini para gerar, avaliar e corrigir redações personalizadas seguindo todos os critérios de correção do ENEM. O sistema conta com uma interface moderna em Tailwind CSS e um backend robusto em Flask.

### 🎯 Funcionalidades Principais

- 🏠 **Página Inicial Interativa**: Menu visual com 6 opções de funcionalidades
- ✏️ **Corrigir Redação**: Envie sua redação e receba análise detalhada em cada competência
- 📝 **Gerar Tema Personalizado**: O aluno digita qualquer tema e a IA gera uma redação única
- 📚 **Estudar Modelos**: Acesse redações nota 1000 com análise completa
- ⭐ **Análise das 5 Competências ENEM**: Avaliação detalhada baseada nos critérios oficiais
- 💡 **Temas Sugeridos**: Banco com 8+ temas prontos para prática nos eixos:
  - 🌱 Meio Ambiente
  - 💻 Tecnologia & Ética
  - ❤️ Saúde Pública
  - 📖 Educação
  - 🎨 Cultura & Sociedade
- 🤖 **Geração com IA**: Deixe a IA gerar redação completa baseada em um tema
- 📋 **Material de Apoio**: Dados, estatísticas e repertório sociocultural para cada tema
- 📤 **Compartilhar**: Copie a redação para compartilhar com colegas
- 📥 **Baixar PDF**: Exporte redações em formato PDF profissional
- 🎨 **Design Moderno**: Interface responsiva com Tailwind CSS e animações suaves
- 🎯 **Filtros por Eixo**: Navegue pelos temas por categoria

## 🚀 Tecnologias Utilizadas

### Backend
- **Python 3.8+**
- **Flask** - Framework web
- **Google Gemini API** - IA para geração de redações
- **Flask-CORS** - Suporte a requisições cross-origin

### Frontend
- **HTML5**
- **Tailwind CSS** - Framework CSS para design moderno
- **JavaScript ES6+** - Interatividade e consumo da API
- **Font Awesome 6.4** - Ícones profissionais
- **html2pdf.js** - Geração de PDFs no navegador

## 📦 Estrutura do Projeto

```
ProjetoComIA_frontend/
├── index.html          # Página principal com todas as funcionalidades
├── readme.md           # Documentação do projeto
└── assets/             # (Opcional) Imagens e recursos estáticos
```

## 🔧 Como Usar

### Instalação

1. **Clone o repositório ou baixe os arquivos**
   ```bash
   git clone https://github.com/seu-usuario/scribmemind.git
   cd scribmemind
   ```

2. **Abra o arquivo `index.html` no navegador**
   - Clique duplo no arquivo, ou
   - Arraste para o navegador, ou
   - Use um servidor local (recomendado para melhor performance)

### Usando com Servidor Local (Recomendado)

**Python 3:**
```bash
cd ProjetoComIA_frontend
python -m http.server 8000
# Acesse: http://localhost:8000
```

**Node.js (com http-server):**
```bash
npm install -g http-server
http-server
# Acesse: http://localhost:8080
```

## 📖 Guia de Uso

### 1. **Página Inicial**
Ao abrir a aplicação, você verá um menu com 6 opções:
- Corrigir Redação
- Gerar Tema
- Estudar Modelos
- Gerar com IA
- Material de Apoio
- Histórico

### 2. **Corrigir Redação**
- Cole sua redação no editor
- A IA analisará e fornecerá feedback detalhado

### 3. **Explorar Temas**
- Escolha um tema na lista ou pesquise por eixo
- Visualize material de apoio com dados e estatísticas
- Estude redações modelo nota 1000
- Gere novas redações com IA

### 4. **Compartilhar e Baixar**
- Use os botões de compartilhamento para copiar redações
- Baixe redações em PDF com formatação profissional

## 🌐 Endpoints da API

A aplicação se conecta aos seguintes endpoints:

```
Backend URL: https://projeto-com-ia-backend.vercel.app

GET  /temas-sugeridos        - Obtém temas sugeridos pela IA
POST /gerar-redacao          - Gera redação baseada em um tema
POST /corrigir-redacao       - Corrige redação enviada
```

## 🎨 Temas de Redação Disponíveis

1. **Caminhos para mitigar a crise hídrica**
2. **Combate ao estigma associado aos transtornos mentais**
3. **Dilemas éticos do desenvolvimento de tecnologias inteligentes**
4. **Desafios da valorização do professor na educação básica**
5. **Impacto das redes sociais na formação da identidade juvenil**
6. **Desafios da mobilidade urbana nas grandes cidades**
7. **Democratização do acesso à tecnologia no Brasil**
8. **Preservação do patrimônio histórico e cultural brasileiro**

## 📊 Competências ENEM Avaliadas

O sistema analisa suas redações de acordo com as 5 competências oficiais:

1. **C1**: Demonstrar domínio da escrita formal
2. **C2**: Compreender a proposta e o gênero textual
3. **C3**: Selecionar, relacionar e organizar informações
4. **C4**: Demonstrar conhecimento dos mecanismos de coesão
5. **C5**: Elaborar proposta de intervenção social

## 🔐 Configuração da API

Para usar a API do Google Gemini, configure a chave de API no backend:

```python
# backend/config.py
GEMINI_API_KEY = "sua-chave-aqui"
```

## 📱 Responsividade

A aplicação é totalmente responsiva e funciona em:
- 💻 Desktop
- 📱 Tablets
- 📲 Smartphones

## 🤝 Contribuições

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

## ⚠️ Requisitos

- Navegador moderno (Chrome, Firefox, Safari, Edge)
- Conexão com internet (para acessar a API)
- JavaScript habilitado

## 🐛 Problemas Conhecidos

- A geração de PDFs funciona melhor em navegadores baseados em Chromium
- Requisições frequentes à API podem ter rate limiting

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## 👨‍💻 Autores

- **Rebeca Diniz** - Desenvolvedora Principal
- [LinkedIn](https://www.linkedin.com/in/rebeca-diniz-970437350/)

## 📧 Contato

Para dúvidas ou sugestões, entre em contato através do LinkedIn ou abra uma issue no repositório.

## 🎯 Roadmap Futuro

- [ ] Autenticação de usuários
- [ ] Histórico de redações salvas
- [ ] Análise comparativa de progressão
- [ ] Chat com IA para dúvidas sobre redação
- [ ] Exportação em múltiplos formatos
- [ ] Sistema de badges e certificados
- [ ] Ranking de melhores redações
- [ ] Integração com LMS (Classroom, Moodle)
