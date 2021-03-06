# MSc Bioinformatics Software Development Group Project 

## Deployed Web Application
http://kincyclopedia.eu-west-2.elasticbeanstalk.com/

## Kincyclopedia: Software Group Development Project
When the complete human genome was sequenced, research into identification and characterisation of human protein kinases became more prevalent. Kinases are a protein class that chemically add phosphoryl groups to themselves (auto-phosphorylation) or other proteins (substrates) through a process called phosphorylation. The sites where phosphorylation occurs are defined as phosphosites.

Kincyclopedia is a web application developed by a group of five students part of the MSc Bioinformatics course from Queen Mary University of London, under the supervision of Prof Conrad Bessant and Dr Fabrizio Smeraldi. The ultimate aim of our application is to act as a central hub for information on human kinases, all of their known phosphosites and kinase inhibitors. 

An important feature apart from the search function is the phosphoproteomics data analysis tool, which produces a result in three categories bar plot representing the relative kinase activity and relative inhibited kinase activity, volcano plot for the complete protein and a volcano plot for all the identified kinases. All the files which were used to these plots can be downloaded for further use.



## Packages required to run the website

bokeh==1.4.0 <br/>
certifi==2019.11.28 <br/>
chardet==3.0.4 <br/>
Click==7.0 <br/>
Flask==1.1.1 <br/>
Flask-SQLAlchemy==2.4.1 <br/>
idna==2.8 <br/>
itsdangerous==1.1.0 <br/>
Jinja2==2.11.3 <br/>
MarkupSafe==1.1.1 <br/>
numpy==1.18.1 <br/>
packaging==20.1 <br/>
pandas==1.0.1 <br/>
Pillow==8.1.1 <br/>
pyparsing==2.4.6 <br/>
python-dateutil==2.8.1 <br/>
pytz==2019.3 <br/>
PyYAML==5.4 <br/>
requests==2.22.0 <br/>
six==1.14.0 <br/>
SQLAlchemy==1.3.13 <br/>
tornado==6.0.3 <br/>
urllib3==1.25.8 <br/>
Werkzeug==1.0.0 <br/>
WTForms==2.2.1 <br/>

You could install all the packages by using the following command:

pip install -r requirements.txt

### Running the website locally

Download the Final_Website folder and run the following command after installing all the packages

python main.py

## Contributors

* [Abhilash R S](https://github.com/A6h9lash) <br/>
* [Arun R](https://github.com/ArunRetnakumar) <br/>
* [Samia A](https://github.com/sasvid) <br/>
* [Solomon P](https://github.com/studgesol) <br/>
* [Tong M](https://github.com/Tong186) <br/>

## Acknowledgments

Thanks to Prof Conrad Bessant and Dr Fabrizio Smeraldi for your support.
