# pandocker-templates

The Official Pandocker Templates Repository

## Installation

To install pandocker and learn how to use, visit [Pandocker Official Repository](https://github.com/luanguimaraesla/pandocker)

## Templates

Here are all the available preconfigured templates.

| name | description |
| ---- | ----------- |
| default | Standard pandocker template. It meets the most basic needs, however it can be completely customized for any need. |
| unb-tcc | Template for the final thesis (_Trabalho de Conclusão de Curso_) at the University of Brasília |
| unb-internship | Template for the final report of compulsory internship at the University of Brasília |
| curriculum | Template for creating a minimalist curriculum |

## Usage

You can use any template by [installing Pandocker](https://github.com/luanguimaraesla/pandocker) and running the following commands:

```bash
mkdir myproject
cd myproject
pandocker new -t [template-name]
sudo chown -R $USER:$USER .
```

## Contributing

You can help us improve this repository. Fork it and create your own template into a directory in the repository root. The directory's name will be the name of the template. Follow the Pandocker documentation and be aware that it will be possible to create and compile the source code with no difficulties. Then, you can submit the template making a Pull Request. :)

Thank you.
