# 💻 Desafio de Phishing para Captura de Senhas do Instagram

## 📜 Descrição
Esse desafio é uma brincadeira com phishing, onde vamos usar algumas técnicas de engenharia social para capturar senhas do Instagram. Mas atenção: isso é só para aprendizado em ambientes controlados e com permissão, beleza? Vamos manter a ética sempre!

## ⚙️ Ferramentas Necessárias
- **VirtualBox**: Um software super útil para criar e gerenciar máquinas virtuais.
- **Kali Linux**: A distro preferida dos hackers éticos, perfeita para testes de segurança.
- **SET (Social-Engineer Toolkit)**: A ferramenta que vai nos ajudar a realizar nossos ataques de engenharia social.
  
## 🛠️ Configurando o Phishing no Kali Linux

1. **Acesso Root**: Abra o terminal e obtenha acesso root com o comando:
   ```bash
   sudo su
   ```

2. **Iniciando o SET**: Execute o Social-Engineer Toolkit:
   ```bash
   setoolkit
   ```

3. **Selecionando o Tipo de Ataque**:
   - Escolha **Social-Engineering Attacks**.

4. **Selecionando o Vetor de Ataque**:
   - Escolha **Web Site Attack Vectors**.

5. **Selecionando o Método de Ataque**:
   - Escolha **Credential Harvester Attack Method**.
   - Em seguida, selecione **Site Cloner**.

6. **Obtendo o Endereço da Máquina**: Para clonar o site, obtenha o endereço IP da sua máquina com:
   ```bash
   ifconfig
   ```

7. **URL para Clonagem**: Insira a URL que deseja clonar:
   ```plaintext
   https://www.instagram.com
   ```

## 📊 Resultados
Após a configuração, você vai poder ver as credenciais que foram capturadas. 
Lembre-se: use essas informações de forma ética e responsável, ok? Divirta-se e aprenda bastante!

![desafio-phishing](https://github.com/user-attachments/assets/82855a91-b9a8-450c-8fee-4b3529075b36)

