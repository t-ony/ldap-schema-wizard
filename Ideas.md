Here are a list of new ideas, features or something that could be cool:

  * Verify the generated schema with slapverify, Same way before start if an ldif or schema or something is provided find the way to verify it. This verifying functions may be in the _ldaputils.py_ module.
  * In order to reuse some attributes, like userPassword, we have to do a list of the objectclasses we consider standards and to define a way to communicate the user that there is a standard attribute that can handle the data-type he/she want to save.
    * mm.. Thinking about the UML tools, when one gonna define a new class attribute, there is a list of existing data-types like int, string, bool, etc... this way the user not have to model his/her own class _String_