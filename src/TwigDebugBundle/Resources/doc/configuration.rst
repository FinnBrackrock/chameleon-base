Configuration
=============

Adding comments for twig includes
---------------------------------
This bundle decorates the include node of twig and adds html comments including the used includes.
You'll have to enable the decorator in your configuration:

.. configuration-block::
    .. code-block:: yaml

        chameleon_system_twig_debug:
          enabled: true
