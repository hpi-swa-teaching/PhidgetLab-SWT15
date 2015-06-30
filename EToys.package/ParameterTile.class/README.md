Represents a parameter in a user-defined script in "classic" tile-scripting.  The type of a script's parameter is declared in the ScriptEditor for the script, and a parameter tile gets its type from the script.  But because the user can change the parameter type *after* having created parameter tiles, we can later have type mismatches.  Which however we at least deal with reasonably cleverly.