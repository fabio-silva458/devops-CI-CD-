





<p align="center">

  <h1 align="center">CI/CD na Prática</h1>





<details open="open">
  <summary>Indice</summary>
  <ol>
    <li>
      <a href="#descrição">Descrição</a>
      <ul>
        <li><a href="#feito-com">Feito Com</a></li>
      </ul>
    </li>
    <li>
      <a href="#começando">Começando</a>
      <ul>
        <li><a href="#requisitos">Requisitos</a></li>
        <li><a href="#executando-local">Executando Local</a></li>
      </ul>
    </li>
    <li><a href="#licença">Licença</a></li>
    <li><a href="#bibliografia">Bibliografia</a></li>
  </ol>
</details>





## Descrição

CI/CD na prática.

Ele contempla uma api simples e o yaml para publicação.

### Feito Com

* [Azure DevOps](https://azure.microsoft.com/pt-br/services/devops/)
* [.net Core](https://dotnet.microsoft.com/download/dotnet/3.1)
* [Azure Cloud](https://portal.azure.com/)




## Começando

Abaixo segue os requisitos como instruções de como rodar a api localmente

### Requisitos

É necessário ter o sdk do [.net Core](https://dotnet.microsoft.com/download/dotnet/3.1) instalado. Além disso uma conta microsoft deve ser criada tanto no [Azure Cloud](https://portal.azure.com/) quanto no [Azure DevOps](https://azure.microsoft.com/pt-br/services/devops/) para realizar a parte do CI/CD de fato.

### Executando Local

2. Copilar e executar a aplicação
   ```sh
   cd src
   dotnet run
   ```


## Licença

Distribuido sob a licença MIT License. Veja `LICENSE` para mais informações.



## Bibliografia
* [Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performin](https://www.amazon.com.br/Accelerate-Software-Performing-Technology-Organizations/dp/1942788339)
* [YAML schema reference](https://docs.microsoft.com/en-us/azure/devops/pipelines/yaml-schema?view=azure-devops&tabs=schema%2Cparameter-schema)
* [Build, test, and deploy .NET Core apps](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/dotnet-core?view=azure-devops&tabs=dotnetfive)




