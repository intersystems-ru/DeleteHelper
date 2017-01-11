# DeleteHelper
A Super class for adding a code-generator %OnDelete method

With regard to making sure that referenced instances are deleted when the referrer is deleted –
This is especially important when purging messaged in Ensemble.
The class includes a Code Generator %OnDelete method, which generates code at compile-time that should take care of deleting persistent objects referenced by the instance being deleted.

What you'd need to do is add this class as another Super class for your class.
There is also an accompanying class that should help with adding this as a Super class for several classes at once (useful for example for classes that were generated by the SOAP Wizard, which might be quite a few).

See class reference documentation for more details.
