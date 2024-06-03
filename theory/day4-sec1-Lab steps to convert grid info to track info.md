# Day 4 - Sec 1 - Timing modelling using delay tables

## Lab steps to convert grid info to track info
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/eca9355d-e43b-4c99-a2e6-50d585e92a32)
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/2baf18ac-6505-477b-9ef2-3ba2243a2b82)
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/17eeffb8-4cdb-4310-a458-86a05b9882c5)

Important points for creating LEF 
* Ports do not mean anything to magic
* Port information is required by the LEF files
* When the design is extracted as LEF, ports become the pins of macro
* More details at https://github.com/ankdesh/vsdstdcelldesign#create-port-definition (fork) 
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/593b140d-503a-443c-b544-5175e860491b)
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/319d8b2d-2844-4294-8458-968005ca6b2d)
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/7ae33aa5-2c26-4380-a56f-4f3d731cfcec)


## Lab steps to convert magic layout to std cell LEF
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/b703f1b0-6716-4726-bdf1-e474f9efd055)
* Defining port
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/006bd2cb-d36f-41ed-a30a-3c744f5024bc)
* Convert to LEF
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/01cdd8b6-a72d-4f61-9e59-fac4dadaa22a)
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/6578259b-eb5f-4f81-a962-07b2ab6776bb)
* My LEF file
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/0f023da9-66ee-4672-8acd-807a1a385041)

### Include the LEF file in the design
* Copy LEF file to the design folder
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/e6718154-fde3-480c-ba7e-073d7cd6c5bc)


## Delay table usage
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/d2fb92b8-35c4-454e-af8f-339322782927)
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/df98d69d-3fd8-4b9e-9650-20957d4b1195)
![image](https://github.com/ankdesh/vsd-openlane/assets/15871819/5740d19c-9570-4dcf-b3b9-3ecb6b2a630c)




