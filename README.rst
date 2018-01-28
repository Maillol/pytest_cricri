pytest-cricri - pytest plugin for cricri
========================================

How to install
--------------

.. code-block:: bash

    $ pip install pytest-cricri

How to launch cricri test
-------------------------

.. code-block:: bash

    $ pytest --cricri test_package_name.test_module_name.TestBaseClass
    
test_package_name should be set in the PYTHONPATH variable.

You can set the max_loop parameters using syntax:

.. code-block:: bash

    $ pytest --cricri test_package_name.test_module_name.TestBaseClass:2
    
Links 
-----
`Cricri project <https://github.com/Maillol/cricri>`_.
`Cricri documentation <http://cricri.readthedocs.io/en/latest/>`_
