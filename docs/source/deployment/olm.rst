Operator Lifecycle Manager (OLM)
--------------------------------

.. note:: For OpenShift environments, replace ``kubectl`` with  ``oc``


The operator is currently available on `OperatorHub <https://operatorhub.io/operator/ibm-spectrum-scale-csi-operator>`_.

1. Install OLM:

.. code-block:: bash
  
  curl -sL https://github.com/operator-framework/operator-lifecycle-manager/releases/download/0.13.0/install.sh | bash -s 0.13.0

2. Download the CSI  ``.yaml`` and apply

.. code-block:: bash

  kubectl create -f https://operatorhub.io/install/ibm-spectrum-scale-csi-operator.yaml


