.. _ansible_documentation:

Ansible Documentation
=====================

About Ansible
`````````````

.. _ansible_documentation:

Ansible Documentation
=====================

Acerca de Ansible
`````````````
Ansible es una herramienta de IT para la automatización. Puede configurar sistemas, desplegar software y orquestar muchas más tareas de IT como; despliegue continuo o actualizaciones continuas sin interrupción del servicio.

Los objetivos principales de ansible son la simplicidad y la facilidad de uso. Tambien esta fuertemente enfocada en fortalecer la seguridad y confiabilidad, con el menor movimiento de partes, usando OpenSSH para transportar (con otros medios de transporte y modos de extracción alternos), y un lenguaje que esta diseñado alrededor de la auditabilidad por humanos incluso aquellos que no esten familiarizados con el programa.

Creemos que la simplicidad es relevante para todos los tipos de ambientes, así que diseñamos para todo tipo de usuarios: developers, sysadmins, release engineers, IT managers y cualquiera en el medio. Ansible es apropiado para manegar todo tipo de ambientes, desde pequeñas instalaciones con un puñado de instancias hasta ambientes con miles de instancias.

Tu puedes puedes aprender mas en `AnsibleFest <https://www.ansible.com/ansiblefest>`_, el evento anual para contribuidores de ansible, usuarios y clientes auspiciado por Red Hat. AnsibleFest es el lugar donde conectar con otros, aprender nuevas habilidades y encontrar un nuevo amigo con el cual automatizar.

Ansible administra maquinas sin agentes de por medio. Nunca existira la duda de como actualizar los demonios remotos o el problema de no poder administrar los sistemas por que los demonios fueron desinstalados. Ya que OpenSSH es uno de los mas proyectos de codigo abiertos más revisados, las brechas de seguridad se reducen considerablemente. Ansible es descentralizado basandose en las credenciales existentes en tu sistema operativo para controlar el acceso a equipos remotos. Si es necesario, Ansible puede ser facilmente conectado con Kerberos, LDAP y otros sistemas centralizados de administraciones de autenticación.

Esta documentación cubre la versión de Ansible anotada en la esquina superior izquierda de esta pagina. Mantenemos multiples versiones de Ansibles y la documentación, así que por favor validad que la versión que estas usando sea la que la documentación cubre. Para recientes caracteristicas, nosotros anotamos la versiónes de Ansible donde la caracteristica fue añadida.

Ansible libera nuevas mejoras de Ansible aproximadamente tres o cuatro veces por año. El core aplicativo evoluciona de manera conservadora, valora la simplicidad en el lenguaje, diseño y configuración. Los contribuidores desarrollan y cambian modulos y complementos, alojados en colleciones desde la versione 2.10, mucho más rapido.


.. toctree::
   :maxdepth: 2
   :caption: Installation, Upgrade & Configuration

   installation_guide/index
   porting_guides/porting_guides

.. toctree::
   :maxdepth: 2
   :caption: Using Ansible

   user_guide/index

.. toctree::
   :maxdepth: 2
   :caption: Contributing to Ansible

   community/index

.. toctree::
   :maxdepth: 2
   :caption: Extending Ansible

   dev_guide/index

.. toctree::
   :glob:
   :maxdepth: 1
   :caption: Common Ansible Scenarios

   scenario_guides/cloud_guides
   scenario_guides/network_guides
   scenario_guides/virt_guides

.. toctree::
   :maxdepth: 2
   :caption: Network Automation

   network/getting_started/index
   network/user_guide/index
   network/dev_guide/index

.. toctree::
   :maxdepth: 2
   :caption: Ansible Galaxy

   galaxy/user_guide.rst
   galaxy/dev_guide.rst


.. toctree::
   :maxdepth: 1
   :caption: Reference & Appendices

   collections/index
   reference_appendices/playbooks_keywords
   reference_appendices/common_return_values
   reference_appendices/config
   reference_appendices/general_precedence
   reference_appendices/YAMLSyntax
   reference_appendices/python_3_support
   reference_appendices/interpreter_discovery
   reference_appendices/release_and_maintenance
   reference_appendices/test_strategies
   dev_guide/testing/sanity/index
   reference_appendices/faq
   reference_appendices/glossary
   reference_appendices/module_utils
   reference_appendices/special_variables
   reference_appendices/tower
   reference_appendices/automationhub
   reference_appendices/logging


.. toctree::
   :maxdepth: 2
   :caption: Release Notes

.. toctree::
   :maxdepth: 2
   :caption: Roadmaps

   roadmap/index.rst
