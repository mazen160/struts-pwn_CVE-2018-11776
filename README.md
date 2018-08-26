*struts-pwn - CVE-2018-11776 Exploit*
============

### An exploit for Apache Struts CVE-2018-11776 ###


# **Usage** #

## Check if the vulnerability exists against a single URL. ##
`python struts-pwn.py --url 'http://example.com/demo/struts2-showcase/index.action'`

## Check if the vulnerability exists against a list of URLs. ##
`python struts-pwn.py --list 'urls.txt'`

## Exploit a single URL. ##
`python struts-pwn.py --exploit --url 'http://example.com/demo/struts2-showcase/index.action' -c 'id'`

## Exploit a list of URLs. ##
`python struts-pwn.py --exploit --list 'urls.txt' -c 'id'`


# **Demo** #
![Demo](https://github.com/mazen160/public/raw/master/static/images/struts-pwn_CVE-2018-11776_Demo.gif)

![Screenshot 1](https://github.com/mazen160/public/raw/master/static/images/struts-pwn_CVE-2018-11776_Screenshot_1.png)

![Screenshot 2](https://github.com/mazen160/public/raw/master/static/images/struts-pwn_CVE-2018-11776_Screenshot_2.png)


# **Requirements** #
* Python2 or Python3
* requests


# **Legal Disclaimer** #
This project is made for educational and ethical testing purposes only. Usage of struts-pwn for attacking targets without prior mutual consent is illegal. It is the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program.


# **License** #
The project is licensed under MIT License.


# **Author** #
*Mazin Ahmed*
* Website: [https://mazinahmed.net](https://mazinahmed.net)
* Email: *mazin AT mazinahmed DOT net*
* Twitter: [https://twitter.com/mazen160](https://twitter.com/mazen160)
* Linkedin: [http://linkedin.com/in/infosecmazinahmed](http://linkedin.com/in/infosecmazinahmed)
