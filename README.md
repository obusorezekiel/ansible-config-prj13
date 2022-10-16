## ANSIBLE DYNAMIC ASSIGNMENTS (INCLUDE) AND COMMUNITY ROLES

Project 13 builds on what we learnt in project 12  and introduces us to another feature *Include*.

### INCLUDE
Include does similar thing as *Imports* but differs because it is dynamic. Dynamic in the sense that ansible is able pick changes in playbooks added to a master playbook in real time. In import ansible preprocesses everything runs the playbook with the data it has. Changes made while executing the playbook is ignored.

### BEST USE OF INCLUDE
Include is best suited for feeding environment variables to ansible.

- Note for most part stick with *Import* statement as *Include* can make debugging difficult.


## When condition

Another important feature in this project is the when condition. It was used to decide the nature of load balancer installed in an environment depending on which variables is set to true

see the code snippet below for better understanding:


See the different load balancers installed sucessfully below:

![Screenshot from 2022-10-14 21-10-16](https://user-images.githubusercontent.com/23356682/196057661-2da90d29-b5d5-49cb-85ba-101f37f93c85.png)
![Screenshot from 2022-10-14 21-41-47](https://user-images.githubusercontent.com/23356682/196057664-53e00e7d-8241-4cea-9db5-3b8f86da78ad.png)
![Screenshot from 2022-10-14 22-00-18](https://user-images.githubusercontent.com/23356682/196057667-7596de70-28e1-4214-aeac-a8988adc7d1e.png)
![Screenshot from 2022-10-14 22-39-12](https://user-images.githubusercontent.com/23356682/196057668-cca21ae7-4aef-4a33-8cfa-9d01b0d1d4c4.png)

