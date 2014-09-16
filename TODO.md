# TODO List

  * Figure out a way to associate a type with a variable, perhaps
    encapsulate a Const subtype in the Var type, yielding something like Var(Num)
    for a variable that is of type Num. This would even let us go through the
    tree at evaluation time and replace the Vars with their corresponding Const
    subtypes with their given values.
  * Consider using a macro for creating new functions and constant types. This
    would allow more complex constructors to be created that would, for example,
    set the arity of the function as a field.
