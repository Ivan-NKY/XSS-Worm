# Self-propagating worm🪱
## a little more complex than mitosis, still fun to watch nonetheless
This project involves the exploitation of a simulated web server using a worm. The project holds similarity to a real world incident known as the [SAMY computor worm](https://en.wikipedia.org/wiki/Samy_(computer_worm)) involving an attack featuring a Cross-Site Scripting (XSS) worm on the networking platform MySpace. Think of this project as a crude copy of this case, still cool nonetheless.  
This project demonstrates innovation, programming skills and knowledge on the exploitation of vulnerable web servers  

## 🌏Environment
* **Web server**: Ubuntu 22 Virtual Machine
*  **Attacker**: Kali Linux

 ## 🧰Tools/Languages
 * BurpSuite
 * JS

## Overview
Given the vulnerability of the website, exploitation may be carried out on this webserver by first developing the payload in JS after analysing clear plaintext header through the usage of a proxy provided by BurpSuite.
After letting our payload run rampant on the web server, we can identify misconfigurations and lack of secure parameters within the source code of the web server, thus leading to such a scenario. More detailed explanations may be reffered to in the file.

## ⚠️Disclaimer
This project was conducted in a controlled environment for educational and research purposes only. Even if the payload only works on vulnerable web servers, this does not excuse you from injecting similar payloads publicly.
