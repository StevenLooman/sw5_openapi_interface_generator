sw5\_openapi\_interface\_generator
----------------------------------

OpenAPI interface generator for Smallworld 5. Reads a OpenAPI (3.0) interface description (JSON) and generates an interface from it.

Once the interface is generated, your can change the generated code. Be aware though, with a re-generate, your changes will be lost.

The base class `openapi_interface_base` should be copied to your own product (mind the license) and altered to suit your needs, or be reimplemented.

Note: This supports only a few basic OpenAPI constructs, namely only those needed at the moment for my own work. If you're missing things, either create an issue or pull request. Though there is of course no guarantee that these will be picked up.


License
-------

This product is licensed under GPLv3. See the file `LICENSE` for more information.
