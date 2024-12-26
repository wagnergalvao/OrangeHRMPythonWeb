# OrangeHRMPythonWeb

Este projeto, OrangeHRMPythonWeb, é um estudo sobre automação web em Python utilizando a plataforma OrangeHRM.

This project, OrangeHRMPythonWeb, is a study on web automation in Python using the OrangeHRM platform.

#### Website &emsp;https://opensource-demo.orangehrmlive.com

### License

Este projeto está licenciado sob a GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007. Para mais informações, consulte o arquivo LICENSE.

This project is licensed under the GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007. For more information, please refer to the LICENSE file.

### Project Structure

OrangeHRMPythonWeb/ <br>
&nbsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; drivers/ <br>
&ensp; &ensp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; chromedriver.exe <br>
&ensp; &ensp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; geckodriver.exe <br>
&ensp; &ensp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; msedgedriver.exe <br>
&nbsp; &nbsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; features/ <br>
&ensp; &ensp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; steps/ <br>
&nbsp; &nbsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; pages/ <br>
&nbsp; &ensp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; reports/ <br>
&nbsp; &ensp; &ensp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; tests/ <br>
&nbsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; .gitignore <br>
&nbsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; LICENSE <br>
&nbsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; README.md <br>

### Virtual Environment Configuration
```
pip install virtualenv
virtualenv venv
```
```
.\venv\Scripts\activate # Windows
```
```
source venv/bin/activate # macOS/Linux
```
### Libraries for Web Automation with Python
#### Biblioteca principal para automação de navegadores &emsp; &emsp; &ensp; pip install selenium
#### Biblioteca principal para configuração de navegadores &emsp; &nbsp; &ensp; pip install webdriver-manager
#### Framework para Behavior Driven Development (BDD) &nbsp; &nbsp; &nbsp; &emsp; pip install behave
#### Framework de testes Python &ensp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &ensp; pip install pytest
#### Biblioteca para requisições HTTP &ensp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; pip install requests
#### Biblioteca para extração de dados HTML e XML &nbsp; &emsp; &emsp; &emsp; &emsp; pip install beautifulsoup4
#### Biblioteca para análise de dados &nbsp; &nbsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; pip install pandas
