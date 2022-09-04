.NET -6

sobre este curso 

1.0.1 Expectativas

-revisão sobre linguagens de programação
- Aprender os fundamentos do C#
- Ter uma experiência real com os itens acima 

_______________________________________________________________

1.0.2 O que são

Definições

- È a forma (Comunicação) comodizermos para o computador
executar algo
- Computadores não falam nossa lingua, usam binário (01010101010)

Definições
- Uma LP faz este intermédio 
- O que  escrevemos será traduzido para binário
-Em resumo temos um arquivo trexto que
- Nós conseguimos ler
- Será traduzido para binário
_________________________________________________________________

Variáveis de Ambiente

Definições

- Desta forma podemos dizer ao .Net qual ambiente
estamos utilizando.


comando no termial

- dotnet run --environment =$ seu_ambiente
                           =$ develoment - ok
                           =$production - ok

- comando run não  executa depuração (debug)

- neste modo sua aplicação não vai parar nos  break points (explicado Adiante)

_____________________________________________________________________________________   

SDK do .NET (6.0.400)
Uso: dotnet [runtime-options] [path-to-application] [arguments]

Execute um aplicativo do .NET.

runtime-options:
  --additionalprobingpath <path>   Caminho contendo a política de investigação e os assemblies a investigar.
  --additional-deps <path>         Caminho para o arquivo deps.json adicional.
  --depsfile                       Caminho para o arquivo <application>.deps.json.
  --fx-version <version>           Versão do Shared Framework instalada a ser usada para a execução do aplicativo.
  --roll-forward <setting>         Role para frente para a versão de estrutura (LatestPatch, Minor, LatestMinor, Major, LatestMajor, Disable).
  --runtimeconfig                  Caminho para o arquivo <application>. runtimeconfig.json.

path-to-application:
  O caminho para um arquivo .dll de aplicativo a ser executado.

Uso: dotnet [sdk-options] [command] [command-options] [arguments]

Execute um comando do SDK do .NET.

sdk-options:
  -d|--diagnostics  Habilitar saída de diagnóstico.
  -h|--help         Mostrar a ajuda da linha de comando.
  --info            Exiba informações do .NET.
  --list-runtimes   Exiba os runtimes instalados.
  --list-sdks       Exiba os SDKs instalados.
  --version         Exiba a versão do SDK do .NET em uso.

Comandos do SDK:
  add               Adicionar um pacote ou uma referência a um projeto do .NET.
  build             Criar um projeto do .NET.
  build-server      Interagir com servidores iniciados por um build.
  clean             Limpar as saídas do build de um projeto do .NET.
  format            Aplicar preferências de estilo a um projeto ou solução.
  help              Mostrar a ajuda da linha de comando.
  list              Listar as referências de um projeto do .NET.
  msbuild           Executar comandos do MSBuild (Microsoft Build Engine).
  new               Criar um novo projeto ou arquivo do .NET.
  nuget             Fornece comandos adicionais do NuGet.
  pack              Criar um pacote do NuGet.
  publish           Publicar um projeto do .NET para implantação.
  remove            Remover um pacote ou uma referência de um projeto do .NET.
  restore           Restaurar as dependências especificadas em um projeto do .NET.
  run               Criar e executar uma saída de projeto do .NET.
  sdk               Gerencie a instalação do SDK do .NET.
  sln               Modificar os arquivos da solução do Visual Studio.
  store             Armazenar os assemblies especificados no repositório de pacotes do runtime.
  test              Executar testes de unidade usando o executor de testes especificado em um projeto do .NET.
  tool              Instalar ou gerenciar ferramentas que ampliam a experiência do .NET.
  vstest            Executar comandos do VSTest (Microsoft Test Engine).
  workload          Gerenciar as cargas de trabalho opcionais.

Comandos adicionais de ferramentas em pacote:
  dev-certs         Crie e gerencie certificados de desenvolvimento.
  fsi               Iniciar F# Interativo / executar scripts do F#.
  sql-cache         SQL Server cache command-line tools.
  user-secrets      Gerencie segredos do usuário de desenvolvimento.
  watch             Inicie um observador de arquivo que executa um comando quando os arquivos são alterados.

Execute 'dotnet [command] --help' para obter mais informações sobre um comando.
