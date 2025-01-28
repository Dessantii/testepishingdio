
# Phishing para Captura de Senhas do Facebook

Este repositório demonstra como realizar um ataque de phishing com o objetivo de capturar credenciais do Facebook utilizando Kali Linux e o setoolkit. **Este repositório tem fins educativos** e deve ser utilizado exclusivamente para testes de segurança em ambientes controlados e com permissão explícita dos alvos.

### Ferramentas Necessárias

- **Kali Linux**
- **setoolkit** (Social Engineering Toolkit)

### Passos para Configuração do Phishing

1. **Acesse o Kali Linux como root**:
   ```bash
   sudo su
   ```

2. **Inicie o setoolkit**:
   ```bash
   setoolkit
   ```

3. **Selecione o tipo de ataque**:
   - Opção: `Social-Engineering Attacks`

4. **Escolha o vetor de ataque**:
   - Opção: `Web Site Attack Vectors`

5. **Escolha o método de ataque**:
   - Opção: `Credential Harvester Attack Method`

6. **Selecione o método de ataque**:
   - Opção: `Site Cloner`

7. **Obtenha o endereço IP da sua máquina**:
   ```bash
   ifconfig
   ```

8. **Clone o site do Facebook**:
   - URL para o clone: `http://www.facebook.com`

### Resultado Esperado

Após seguir os passos acima, você terá uma página de login clonada do Facebook que captura as credenciais fornecidas pelos usuários.

![image]([https://github.com/user-attachments/assets/cca73768-ddaa-4477-9849-f08bc6fb8628](https://github-production-user-asset-6210df.s3.amazonaws.com/92925579/407538749-a154b78f-c5bf-4efd-9911-72e98c020b81.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20250128%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250128T232949Z&X-Amz-Expires=300&X-Amz-Signature=a1b0b2ae0f560329f1ce502c2c5c0cca67b3ecc4613187d9e70ea901957a5742&X-Amz-SignedHeaders=host))

### Aviso Legal

Este material tem fins exclusivamente educativos. **Não utilize este procedimento em sistemas sem permissão**. A prática de phishing é ilegal e antiética quando realizada sem o consentimento explícito do alvo.
