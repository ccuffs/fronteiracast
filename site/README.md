
# Podcast FronteiraCast

  O FronteiraCast é um novo projeto de cultura que está sendo realizado por estudantes de Ciência da Computação da UFFS Campus Chapecó em conjunto com o coordenador do curso Fernando Bevilacqua e professor Maurício Bozatski da área da Filosofia.


#### O projeto foi criado pelo curso de Ciência da Computação mas é destinado não só a toda comunidade acadêmica da Universidade Federal da Fronteira Sul como público em geral.




## Contribuiçõs para o repositório: preparando o ambiente


**1 - git:** vamos precisar colocar o site no GitHub para servi-lo:

'''
sudo apt install git
'''

**2 - ruby-full:** uma versão antiga mais estável do Ruby. Como Jekyll foi feita nessa lingaguem precisamos dela instalada no seu computador:

'''
sudo apt install ruby-full
'''

**3 - rubygems:** Assim como o pip para Python e o npm para o mundo Node, existe o gem para ruby. Ele é um gerenciador de pacotes e ele que precisaremos para instalar jekyll e os demais pacotes para o Fresh:

'''
sudo apt install rubygems       # ou rubygems-integration
'''

**4 - bundler:** No melhor esquema Inception o bundler é um pacote que controla outros pacotes, ele controla versões dos pacotes e suas dependências nos projetos:

'''
gem install jekyll bundler
'''


## Baixando o tema

Pode ser feito de duas maneiras, ou pode realizar um Fork a partir do link: ** https://github.com/ccuffs/poduffs **

'''
git clone https://github.com/ccuffs/poduffs
'''


## Rodando o Projeto

Depois de clonar o repositório em sua máquina, acesse a pasta via terminal e rode os seguintes comandos: 

'''
cd repositório
bundle install
bundle exec jekyll serve
'''


# Muito obrigado!
