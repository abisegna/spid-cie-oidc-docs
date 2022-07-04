.. include:: ./common_definitions.rst

metadata OIDC
-------------

OIDC-FED utilizza ed estende i claim dei metadata così come definiti all'interno delle specifiche di OpenID Connect Discovery 1.0 e OpenID Connect Dynamic Client Registration 1.0 `OpenID.Discovery`_, `OpenID.Registration`_ rispettivamente per OP e RP. 

In OIDC-FED il metadata OIDC relativo a RP e OP viene definito all'interno del claim **metadata** e del suo sotto claim **<entity_type>**, all'interno dell'Entity Configuration, come oggetto JSON.


.. toctree:: 
   :maxdepth: 1

   metadata_oidc_op.rst
   metadata_oidc_rp.rst
   metadata_oidc_fa.rst
   metadata_oidc_altri.rst
