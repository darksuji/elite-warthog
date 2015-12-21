Thrustmaster HOTAS Warthog bindings for Elite: Dangerous
--------------------------------------------------------

Each directory corresponds to a different version of Elite.  Each configuration contains a few files:

 * A `.fcf` file used by the TARGET GUI.  This can be loaded with the 'Edit Configuration' dialog in TARGET to install it in the GUI Configuration Files list.
 * One of more `.tmc` files used by TARGET for actual configuration.  These have to live in `%AppData%\Thrustmaster\TARGET\Scripts`.  They are not considered canonical by the GUI and it will overwrite them with abandon.  I recommend just putting them somewhere else and loading them from the TARGET Script Editor.
 * A `.binds` file to provide the corresponding control bindings in Elite.  These are version specific (duh) and live in `%LocalAppData%\Frontier Developments\Elite Dangerous\Options\Bindings`.
 * (add more as we discover them)
