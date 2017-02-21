sa-secure-automatic-updates
===========================

[![Build Status](https://travis-ci.org/softasap/sa-secure-automatic-updates.svg?branch=master)](https://travis-ci.org/softasap/sa-secure-automatic-updates)


Forces automatic installation of the security updates on Ubuntu 16.04 LTS servers



Example of use:
```YAML

     - {
         role: "sa-secure-automatic-updates"
       }

```

Advanced:
```YAML
     - {
         role: "sa-secure-automatic-updates"
       }
```

See box-example for standalone installation example


Usage with ansible galaxy workflow
----------------------------------

If you installed the sa-secure-automatic-updates role using the command


`
   ansible galaxy install softasap.sa-secure-automatic-updates
`

the role will be available in the folder library\softasap.sa-secure-automatic-updates.
Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa-secure-automatic-updates"
       }

```


Copyright and license
---------------------

Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)


