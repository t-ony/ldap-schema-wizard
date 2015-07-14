This specification state _needs_, _characteristics_, _restrictions_ and _requirements_ this project must satisfy.

# Needs #
High level statements that represents the business need, the real problem that the solution intend to solve.

  * To make a LDAP schema specification for most of the LDAP implementations in a easy way and whithout any LDAP schema syntax knowledge.
  * Given a LDAP schema convert it to another implementation syntax or format.

# Characteristics #
The solution MUST permit to:

  * Convert between LDAP schema formats
  * Create objectclass definitions and its attributes from the classes of a model.
  * Input objectclasses and attributes OID by the user or assign one automatically from a test branch in the OID namespace.
  * Select attribute types from a list automatically generated from a specified LDAP server
  * Give the option to assign as attribute type, members of existent classes in order to create a cross-reference (DN type) between objects in the DIT.


# Restrictions #
This statements are no negotiable:

  * Must be developed using Python

# Functional requirements #

# Non functional requirements #