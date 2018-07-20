Test Failover
-------------

From the Super-NetOps terminal, run the handy lab-info utility. Confirm that "MCPD is up, System Ready" for all three of your instances.

.. code-block:: bash

   lab-info

.. image:: ./images/1_force_standby.png
  :scale: 50%

.. image:: ./images/2_force_standby_confirm.png
  :scale: 50%

.. image:: ./images/3_terraform_failover_eip.png
  :scale: 50%

.. image:: ./images/4_https_standby_az1.png
  :scale: 50%

.. image:: ./images/5_disable_node1.png
  :scale: 50%

.. image:: ./images/5_https_standby_az2.png

.. attention ::
   
   Do not attempt to reset the Big-IP password until **MCPD is up, System Ready**.

