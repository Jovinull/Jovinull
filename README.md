<p align="center">
  <img src="./assets/banner.png" alt="Banner do perfil de Felipe Jovino" width="100%" />
</p>

<h1 align="center">Felipe Jovino</h1>
<p align="center">
  IT Coordinator · Full-Stack (AdonisJS/Next.js) · AI/ML Research · IoT/ESP32 · Educador · CTO @ AccessSim
</p>

<p align="center">
  <a href="#sobre-mim">Sobre</a> ·
  <a href="#agora">Agora</a> ·
  <a href="#projetos-destaque">Projetos</a> ·
  <a href="#stack">Stack</a> ·
  <a href="#publicacoes--reconhecimentos">Publicações & Reconhecimentos</a> ·
  <a href="#linha-do-tempo">Linha do tempo</a> ·
  <a href="#contato">Contato</a>
</p>

---

## Sobre mim
Sou desenvolvedor full-stack com foco em **AdonisJS v6, Next.js e PostgreSQL**, pesquisador em **IA/ML** e entusiasta de **IoT/ESP32**. Trabalho guiado por arquitetura limpa, documentação sólida e entrega consistente — alinhando engenharia a impacto real (saúde pública, acessibilidade e educação). Coordeno times, escrevo e ensino para que boas soluções sejam replicáveis e manteníveis.

- **Hoje:** Coordenação de TI e liderança técnica, padronizando processos (GitFlow, CI/CD, qualidade) e entregas full-stack.
- **P&D:** Visão computacional e aprendizado de máquina aplicados; soluções locais/privadas quando necessário.
- **Educação:** Produção de conteúdo técnico que encurta a curva de aprendizado com exemplos práticos e contexto.

> *“Software robusto nasce de clareza: boas interfaces, dados bem modelados e processos previsíveis.”*

---

## Agora
- **Sistemas**: padronização de camadas (Controller → Service → Repository), validações com **VineJS**, RBAC e testes.
- **Frontend**: Next.js (App Router), **Tailwind** e design consistente (modo escuro/tema).
- **Pesquisa**: pipelines de **ML** reprodutíveis e LoRA local; experimentos de **RL** no jogo Snake.
- **Conteúdo**: capítulos técnicos sobre **Ciclo HTTP & HttpContext**, **Config/ENV** e **Lucid**.

---

## Projetos (destaque)

<!-- Observação de assets necessários (adicione em ./assets/projetos/):
bithunter.png · glicemy.png · domuserve.png · iot-residuos.png · signforest.png · irriga.png
-->

<table>
  <tr>
    <td width="50%" valign="top">
      <img src="./assets/projetos/bithunter.png" alt="BitHunter" />
      <h3><a href="https://github.com/Jovinull/BitHunter">BitHunter</a></h3>
      <p>
        RPG 2D top-down de ação e exploração com progressão longa e rejogabilidade.
        Sem narrativa linear, o jogador navega por áreas interconectadas e
        <em>dungeons</em> de profundidade infinita, com escalonamento claro de risco/recompensa.
        O foco é um ciclo direto e viciante: explorar → enfrentar inimigos → coletar recursos →
        evoluir personagem e equipamento. Visão de longo prazo: coop, roda de habilidades à la Tibia,
        refino/nível de equipamentos e sistema de ascensão com bônus permanentes.
      </p>
      <p><strong>Pilares:</strong> leitura visual limpa, desempenho estável, atualizações frequentes e balanceamento transparente.</p>
      <p><strong>Stack:</strong> Java puro + AWT/Swing · pixel art · áudio leve em loop.</p>
    </td>
    <td width="50%" valign="top">
      <img src="./assets/projetos/glicemy.png" alt="Glicemy" />
      <h3><a href="https://github.com/Jovinull/glicemy-back">Glicemy</a></h3>
      <p>
        API para monitoramento de Diabetes: registro de glicemia, administração de medicamentos,
        lembretes e geração de relatórios. Foco em segurança desde o desenho:
        autenticação JWT, criptografia de dados sensíveis e arquitetura para integração
        com dispositivos de medição.
      </p>
      <p><strong>Stack:</strong> Node.js/Express · TypeScript · PostgreSQL/Prisma · REST.</p>
    </td>
  </tr>

  <tr>
    <td width="50%" valign="top">
      <img src="./assets/projetos/domuserve.png" alt="DomusServer/DomusLink" />
      <h3>DomusServer + DomusLink</h3>
      <p>
        Plataforma IoT com <strong>ESP32</strong>, sensores DHT22/HC-SR04/MQ-02 e comunicação
        <strong>MQTT/TLS</strong>. Arquitetura em máquina de estados (baseada em <code>millis()</code>)
        para execução assíncrona, módulos independentes (rede/MQTT, sensores, publicação) e tópicos
        padronizados para automações e dashboards.
      </p>
      <p><strong>Objetivos:</strong> telemetria em tempo real, comunicação segura (8883), modularidade e manutenção simples.</p>
      <p><strong>Stack:</strong> C++ (ESP32) · MQTT (HiveMQ) · Dashboard/Integrações via Node/Flask.</p>
    </td>
    <td width="50%" valign="top">
      <img src="./assets/projetos/iot-residuos.png" alt="IoT Gestão de Resíduos Sólidos Urbanos" />
      <h3><a href="https://github.com/Jovinull/IoT-Gestao-Residuos-Solidos-Urbanos">IoT — Gestão de Resíduos</a></h3>
      <p>
        Arquitetura de IoT para gestão de resíduos sólidos urbanos com ênfase em
        eficiência energética e comunicação assíncrona via <strong>MQTT</strong>.
        Integra coleta de dados em tempo real, dispositivos de campo e camada de aplicação,
        conectando revisão de literatura, desenho de arquitetura e implementação prática.
      </p>
      <p><strong>Stack:</strong> ESP32 · MQTT · APIs · Visualização/Web.</p>
    </td>
  </tr>

  <tr>
    <td width="50%" valign="top">
      <img src="./assets/projetos/signforest.png" alt="SignForest" />
      <h3><a href="https://github.com/Jovinull/SignForest">SignForest</a></h3>
      <p>
        Reconhecimento de sinais em Libras combinando <strong>MediaPipe</strong> (landmarks de mãos)
        com <strong>Random Forest</strong>. Pipelines de criação de dataset, treino, busca de
        hiperparâmetros e <em>inference</em> em tempo real via webcam, com métricas de avaliação
        e salvamento do modelo para produção.
      </p>
      <p><strong>Stack:</strong> Python · CV/ML · MediaPipe · scikit-learn.</p>
    </td>
    <td width="50%" valign="top">
      <img src="./assets/projetos/irriga.png" alt="IrrigaControll" />
      <h3><a href="https://github.com/Jovinull/IrrigaControll">IrrigaControll</a></h3>
      <p>
        Sistema de irrigação automática com <strong>ESP32</strong>, DHT22 e sensor de umidade do solo,
        controlando relé com base em leituras ambientais. Exposição de API HTTP no dispositivo e
        <strong>dashboard Flask</strong> para visualização e acompanhamento em tempo real.
      </p>
      <p><strong>Stack:</strong> C++ (ESP32) · Flask · HTML/CSS/JS.</p>
    </td>
  </tr>
</table>

<details>
  <summary><strong>Mais repositórios</strong> (abrir)</summary>

- <a href="https://github.com/Jovinull/aracaju-mais-digital">aracaju-mais-digital</a> — TypeScript · projeto público
- <a href="https://github.com/Jovinull/AppletPlayground">AppletPlayground</a> — Java (compatível JDK 8/OpenJDK8)
- <a href="https://github.com/Jovinull/landingpage-acesssim">landingpage-acesssim</a> — TypeScript
- <a href="https://github.com/Jovinull/cad-preproc">cad-preproc</a> — Python
- <a href="https://github.com/Jovinull/Valtherium">Valtherium</a> — (público)
- <a href="https://github.com/Jovinull/idle-mine-redux">idle-mine-redux</a> — fork JS
- <a href="https://github.com/Jovinull/glicemy-back">glicemy-back</a> — Node/Express/Prisma (privado)
- <a href="https://github.com/Jovinull/LeafLink">LeafLink</a> — B+ Tree em Python (público)
- <a href="https://github.com/Jovinull/Image-Showcase">Image-Showcase</a> — Flask + Bootstrap
- <a href="https://github.com/Jovinull/Flask-Web">Flask-Web</a> — Monólito Flask + MySQL
- <a href="https://github.com/Jovinull/Estrutura-Dados-Python">Estrutura-Dados-Python</a>
- <a href="https://github.com/Jovinull/Breast-Cancer">Breast-Cancer</a>
- <a href="https://github.com/Jovinull/Two-Player-PyChess">Two-Player-PyChess</a>
- <a href="https://github.com/Jovinull/IoT-Gestao-Residuos-Solidos-Urbanos">IoT-Gestão-Resíduos</a>
</details>

---

## Stack

<!-- Faixa de ícones (apenas o que existe em ./assets/icons). Use height/width em atributos, não em style. -->
<p align="center">
  <img src="./assets/icons/typescript.svg" alt="TypeScript" height="28">
  <img src="./assets/icons/nodejs.svg"     alt="Node.js"    height="28">
  <img src="./assets/icons/nextjs.svg"     alt="Next.js"    height="28">
  <img src="./assets/icons/react.svg"      alt="React"      height="28">
  <img src="./assets/icons/tailwindcss.svg" alt="Tailwind CSS" height="28">
  <img src="./assets/icons/postgresql.svg" alt="PostgreSQL" height="28">
  <img src="./assets/icons/python.svg"     alt="Python"     height="28">
  <img src="./assets/icons/java.svg"       alt="Java"       height="28">
  <img src="./assets/icons/docker.svg"     alt="Docker"     height="28">
  <img src="./assets/icons/vscode.svg"     alt="VS Code"    height="28">
  <img src="./assets/icons/adonisjs.svg"   alt="AdonisJS"   height="28">
  <img src="./assets/icons/arduino.svg"    alt="Arduino/ESP32" height="28">
</p>

**Linguagens:** TypeScript · JavaScript · Python · Java · C/C++  
**Back-end:** AdonisJS 6 (Lucid, VineJS/Bouncer) · Node/Express · Flask · PostgreSQL · JWT/RBAC  
**Front-end:** Next.js (App Router/SSR) · React · Tailwind · Zustand  
**IA/ML:** scikit-learn · (PyTorch quando necessário) · Rasa · Whisper  
**IoT:** ESP32/Arduino · MQTT · React Native (Expo)  
**Dev-Ops:** Git/GitHub · Docker · Vercel · Linux

<!-- Grade responsiva somente com ícones que você tem no repo -->
<table>
  <tr>
    <td align="center"><img src="./assets/icons/adonisjs.svg"    height="32" alt="AdonisJS"><br><sub>AdonisJS</sub></td>
    <td align="center"><img src="./assets/icons/nextjs.svg"      height="32" alt="Next.js"><br><sub>Next.js</sub></td>
    <td align="center"><img src="./assets/icons/react.svg"       height="32" alt="React"><br><sub>React</sub></td>
    <td align="center"><img src="./assets/icons/typescript.svg"  height="32" alt="TypeScript"><br><sub>TypeScript</sub></td>
    <td align="center"><img src="./assets/icons/nodejs.svg"      height="32" alt="Node.js"><br><sub>Node.js</sub></td>
    <td align="center"><img src="./assets/icons/postgresql.svg"  height="32" alt="PostgreSQL"><br><sub>PostgreSQL</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="./assets/icons/python.svg"      height="32" alt="Python"><br><sub>Python/ML</sub></td>
    <td align="center"><img src="./assets/icons/java.svg"        height="32" alt="Java"><br><sub>Java</sub></td>
    <td align="center"><img src="./assets/icons/tailwindcss.svg" height="32" alt="Tailwind CSS"><br><sub>Tailwind</sub></td>
    <td align="center"><img src="./assets/icons/docker.svg"      height="32" alt="Docker"><br><sub>Docker</sub></td>
    <td align="center"><img src="./assets/icons/vscode.svg"      height="32" alt="VS Code"><br><sub>VS Code</sub></td>
    <td align="center"><img src="./assets/icons/arduino.svg"     height="32" alt="Arduino/ESP32"><br><sub>Arduino/ESP32</sub></td>
  </tr>
</table>

> Nota: GitHub sanitiza HTML no README (remove CSS/`style` e afins); coloque **uma linha em branco** para sair de blocos HTML antes de continuar em Markdown.  

---

## Publicações & Reconhecimentos
- **Artigos:** *Acesso à formação em IA para pessoas de baixa renda (Estudo de Caso em Sergipe)* · *Fronteiras entre humanidade e tecnologia: a ética da IA*.  
- **Certificações:** Oracle Cloud Infrastructure — AI Foundations Associate.  
- **Prêmios:** Melhor Artigo (SEMEXT/IFS) · Segundo Melhor Artigo (SNCT/IFS).

---

## Snippets (estilo de código)

```ts
// Contrato base de Service em AdonisJS v6
export interface IService<T, CreateDTO, UpdateDTO> {
  index(params?: Partial<T>): Promise<T[]>
  show(id: string | number): Promise<T>
  store(payload: CreateDTO): Promise<T>
  update(id: string | number, payload: UpdateDTO): Promise<T>
  destroy(id: string | number): Promise<void>
}
````

```python
# Pipeline simples de features para séries temporais
def add_indicators(df):
    df["sma_10"] = df["close"].rolling(10).mean()
    df["ema_10"] = df["close"].ewm(span=10, adjust=False).mean()
    return df.bfill()
```

---

## Linha do tempo

```mermaid
timeline
  title Marcos recentes
  2023 : Pesquisa aplicada em IA/IoT : Consolidação de projetos educacionais
  2024 : Padronização full-stack (Adonis/Next) : Premiações acadêmicas
  2025 : Coordenação de TI : Acesso/AccessSim e conteúdos técnicos
```

---

## Idiomas

Português (nativo) · Inglês (profissional) · Espanhol (profissional) · Libras (intermediário)

---

## Contato

* **E-mail:** [felipejovinogamerplay@gmail.com](mailto:felipejovinogamerplay@gmail.com)
* **GitHub:** <a href="https://github.com/Jovinull">github.com/Jovinull</a>
* **LinkedIn:** <a href="https://www.linkedin.com/in/jobas">linkedin.com/in/jobas</a>
* **Lattes:** <a href="http://lattes.cnpq.br/8481399564892228">lattes.cnpq.br/8481399564892228</a>

---

<p align="center">
  <sub>Este README usa apenas Markdown/HTML nativos do GitHub e imagens locais em <code>./assets</code>.</sub>
</p>
