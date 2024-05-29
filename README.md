
Bem-vindo ao repositório GitHub do Flutter-TDD-Clean-Architecture-E-Commerce-App! Este projeto é uma vitrine das práticas modernas de desenvolvimento de aplicativos móveis, aproveitando o poder do Flutter, do Test-Driven Development (TDD), da Clean Architecture e do pacote BLoC (Business Logic Component). Construído usando a versão mais recente do Flutter 3, este aplicativo de comércio eletrônico exemplifica as melhores práticas para a criação de aplicativos Flutter escaláveis, sustentáveis e eficientes.

## Key Features:

* **Test-Driven Development (TDD)**: Este projeto enfatiza a importância de escrever testes antes de escrever o código real. Ele garante que a lógica do aplicativo seja exaustivamente testada, aumentando a confiabilidade e a capacidade de manutenção.
* **Arquitetura limpa**: O aplicativo segue uma arquitetura limpa e modular que separa as preocupações em diferentes camadas: Apresentação, Domínio e Dados. Essa arquitetura promove a reutilização de código e facilita a adaptação a mudanças no futuro.
* **BLoC State Management**: O aplicativo utiliza o padrão BLoC para gerenciamento de estado. O BLoC ajuda a gerenciar o fluxo de dados e a lógica de negócios de maneira limpa e reativa, melhorando o desempenho geral do aplicativo.
* **Funcionalidade de comércio eletrônico**: O aplicativo apresenta uma variedade de recursos de comércio eletrônico, como navegação de produtos, pesquisa, carrinho e compras. Os usuários podem explorar produtos, adicioná-los ao carrinho e concluir transações sem problemas.
<!-- Features -->
---
| Feature       | UseCases                                                                                                                                                                                                   |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Product       | Get Product UseCase                                                                                                                                                                                        |
| Category      | Get Cached Category UseCase<br/>Get Remote Category UseCase<br/>Filter Category UseCase                                                                                                                    |
| Cart          | Get Cached Cart UseCase<br/>Get Remote Cart UseCase<br/>Add Cart Item UseCase<br/>Sync Cart UseCase                                                                                                        |
| User          | Get Cached User UseCase<br/>SignIn UseCase<br/>SignUp UseCase<br/>SignOut UseCase                                                                                                                          |
| Delivery Info | Get Cached Delivery Info UseCase<br/>Get Remote Delivery Info UseCase<br/>Add Delivery Info UseCase<br/>Edit Delivery Info UseCase<br/>Select Delivery Info UseCase<br/>Get Selected Delivery Info UseCase |
| Order         | Get Orders UseCase<br/>Add Order UseCase                                                                                                                                                                   |

---

## Demo Sample

<div style="text-align: center">
    <table>
        <tr>
            <td style="text-align: center">
                <img src="https://res.cloudinary.com/dhyttttax/image/upload/v1695741758/RepoAssets/home-loading_r39lc6.gif" width="200"/>
            </td>            
            <td style="text-align: center">
                <img src="https://res.cloudinary.com/dhyttttax/image/upload/v1695743869/RepoAssets/home-navigation-min_q1cou5.gif" width="200"/>
            </td>
            <td style="text-align: center">
                <img src="https://res.cloudinary.com/dhyttttax/image/upload/v1695744798/RepoAssets/product-details-order_j0lvw5.gif" width="200" />
            </td>
        </tr>
        <tr>
            <td style="text-align: center">
                <img src="https://res.cloudinary.com/dhyttttax/image/upload/v1695745493/RepoAssets/user-delivery-infomarion_zr1eyv.gif" width="200"/>
            </td>
            <td style="text-align: center">
                <img src="https://res.cloudinary.com/dhyttttax/image/upload/v1695746530/RepoAssets/user-auth-screens_k3h6fw.gif" width="200"/>
            </td>
            <td style="text-align: center">
                <img src="https://res.cloudinary.com/dhyttttax/image/upload/v1695747060/RepoAssets/user-sign-in-loading_qjqmt0.gif" width="200"/>
            </td>
        </tr>
    </table>
</div>

## Contributing:

Agradeço as contribuições da comunidade Flutter para tornar este projeto ainda melhor. Se você está interessado em adicionar novos recursos, corrigir bugs ou melhorar a documentação, suas contribuições são muito apreciadas. Consulte as diretrizes de contribuição no repositório para obter mais detalhes sobre como participar.

<!-- GETTING STARTED -->
## Getting Started

Para começar com este projeto, siga as instruções no LEIA-ME para configurar seu ambiente de desenvolvimento e executar o aplicativo localmente. Você também pode explorar a arquitetura, os testes e a documentação do projeto para obter insights sobre a criação de aplicativos Flutter robustos.

Esperamos que este Flutter-TDD-Clean-Architecture-E-Commerce-App sirva como um recurso valioso para entusiastas e desenvolvedores do Flutter que desejam aprender sobre TDD, arquitetura limpa e BLoC no contexto do desenvolvimento de aplicativos móveis. Happy coding!

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/MiguelPereiraDantas/Flutter.git
   ```
2. Install packages
   ```sh
   flutter pub get
   ```
3. Run app
   ```sh
   flutter run lib/main.dart
   ```
4. Run test
   ```sh
   flutter test
   ```
Para obter ajuda para começar a usar o Flutter, consulte a
[documentation](https://flutter.io/).

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.
