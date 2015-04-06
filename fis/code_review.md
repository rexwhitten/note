Code Review Notes 
==========================================
- 4/6/2015 
- ---------------------------------------
- Globally Refactor.
- -------------------

# Core ( abstract )
--------------------------------------------------
- Abstract Implementation. 
- 

# Infrastructure ( Domain Implementation ) 
--------------------------------------------------
- Concrete Domain Implementation

# Variables 
---------------------------------------------------
- private module level variables this._var  notation 
- everything should be in camel case. 


# Services 
---------------------------------------------------
- Method Names ( [Verb][Boundary][Type] ) 
- Shields the persistence mechanism 

# Repositories
---------------------------------------------------
- Repository Queries - Implement Repository Queryables (a)
- This would include - template
- IEnumerable Return Types



# Strategy to show Success/Warning/Error
--------------------------------------------------
- Specific information to a user.
- Specific information to show information.
- Specific handling exception(s).
- How to handle missing/none/ and empty data set. 

