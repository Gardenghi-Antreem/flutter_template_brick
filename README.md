# flutter_template_brick

[![Powered by Mason](https://img.shields.io/endpoint?url=https%3A%2F%2Ftinyurl.com%2Fmason-badge)](https://github.com/felangel/mason)

this is a [mason][1] brick that generate the structure for a flutter project

❗ Note: use this template before inizialize your project repository

## Getting Started 🚀

for use this birck you need to:
- download this repo in a foulder different form your project foulder
- lunch in your project foulder the command 
    ```sh
    dart pub global activate mason_cli
    mason init
    ```
- in your poject foulder add the flutter_template_gellify brick in the mason.yaml:
    ```yaml
      bricks:
        flutter_template_gellify:
          path: path/to/flutter_template_brick
    ```
- open the terminal inside your project foulder e type the following command:
    ```sh
    mason add flutter_template_brick
    mason make flutter_template_brick
    ```

❗ Note: is better to inizialize your project repository only inside the generate template foulder


[Official Mason Documentation][2]

[1]: https://github.com/felangel/mason
[2]: https://docs.brickhub.dev

