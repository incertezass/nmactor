Verificador de IP com Nmap
Este é um software simples de verificação de IP, utilizando a ferramenta Nmap para realizar varreduras de segurança e detecção de vulnerabilidades. O programa permite que você execute varreduras básicas e avançadas em qualquer endereço IP, verificando portas abertas, serviços e até mesmo vulnerabilidades conhecidas.

Funcionalidades:
Verificação Simples: Realiza uma varredura básica no IP fornecido.
Verificação Avançada: Permite a escolha de diferentes opções de varredura, como detecção de versão e verificação de portas específicas.
Verificação de Vulnerabilidades: Executa uma verificação de vulnerabilidades utilizando os scripts do Nmap.
Relatório de Resultados: Os resultados das varreduras podem ser salvos em arquivos de texto para análise posterior.
Como Usar:
Instalar o Nmap:

Certifique-se de que o Nmap está instalado no seu sistema. Caso contrário, instale-o conforme a documentação oficial:
Instalação do Nmap
Baixar o Projeto:

Clone este repositório usando o Git:
git clone https://github.com/incertezass/nmactor.git
Acessar o Diretório:

Navegue até o diretório do projeto:
cd nmactor
Executar o Programa:

Execute o arquivo Python:
python nmactor.py
Escolha a Opção de Verificação:

Você será solicitado a inserir um endereço IP para a varredura.
Escolha uma das opções de varredura (simples, avançada, vulnerabilidades).
Requisitos:
Python 3.x
Nmap instalado no sistema
colorama ("SE TUDO DER CERTO, ELE BAIXARA AUTOMATICAMENTE")
