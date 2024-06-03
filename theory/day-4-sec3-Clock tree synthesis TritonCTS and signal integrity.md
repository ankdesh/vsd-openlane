# Day 4 - Sec 3 - Clock tree synthesis TritonCTS and signal integrity

## Clock tree routing and buffering using H-Tree algorithm
* Naive Tree
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/08cedcef-9051-49df-a41a-0e56b8adf10e)
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/65bcb789-829e-4311-b716-d0895a90f305)
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/3ba29c9b-b7e0-405c-8b85-9e7ac0d4379e)

* H-Tree
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/113ba3f8-8603-4ee4-a0e0-6d0092d9517e)

* Add buffers to keep clock signal integrity intact
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/a68d05df-bbc8-4254-9bc4-9c0b1bbe9dfd)

* Shielding clock
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/b4e244b8-0b15-4a62-898e-eef470dad4b1)

* What's a glitch
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/f8f07016-6746-41d0-9ce0-9b89876767fd)

##  Lab steps to run CTS using TritonCTS
* Run the CTS with run_cts command
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/16a830f9-417e-4e2a-96a5-61002c873a89)
* A new netlist is created after CTS command
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/e91925ec-ca80-45cd-b429-05e2684772b6)
