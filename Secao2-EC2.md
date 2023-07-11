Nesta seção veremos:

- EC2 - Elastic Computer Cloud, que são maquinas virtuais que podemos alugar da aws e usar para hospedagem
  - Computador totalmente adaptavel (RAM, SO, HDD ou SSD)
- BootStrap é um scrip que ser lido apenas uma vez na inicialização com as configurações que voce definiu. POde ser um update, uma pagina html, etc...
- Na criação voce ja escolhe as configuraçãoes e pode ir personalizando, como RAM, SO, espaço e etc...
- Depois de criando da para acessar, para e excluir muito rapidamente a instancia.
- Quando uma instncia é recriada muito provevel que o IP publico seja alterado e voce tenha que atualizar est IP onde estiver usando.
- EC2 são instancias e existem muitas disponiveis, neste doc existem algumas e suas principais finalidades pois ja estão otimizadas [EC2](https://aws.amazon.com/ec2/instance-types/)
- Sempre usar polices para anexar regas no EC2 nunca colocar as credenciais pelo shell do browser
  
  > - Estudar mais sobres as opções de planos e suas diferenças
- EBS -Elastic Block Store - são espaços para armazenar dados e podem ser usados e reusados de uma instancia para outra, mas não podem ser utilizados de uma região para outra
  - Exemplo: não pode ser criado na região ca-central-1 (Canada) e ser realocado para a sa-east-1(São Paulo)
- Um EBS só pode ser usado por um EC2 por vez, mas um EC2 pode ter 2 ou mais EBS
- Os EBS podem ser criados e não anexados para alguma EC2
- O recurso EBS Snapshot serve de backup para copiar um EBS de uma Avaliable Zone (AZ) para outra



- AMI - Amzon Machine Image, são instancias customizadas que o usuario pode criar e posteriormente copiar e usar estas AMI's com o intuito de otimizar tempo de inicialização

- Podemos criar as AMI's totalente personalizdas na parte de hardware tambem, como armazenamento, RAM, performance etc...

- 
