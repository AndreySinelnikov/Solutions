### CONTEXT:

There is a GitHub Enterprise repository you have access to, and you have to clone it. 
However, dealing with SSH keys is sort of a hassle and you'd want to set up simpler authentication method.

### SOLUTION:

1. IN Intellij IDEA start screen, 
    SELECT 'Get from VCS'
    
2. IN 'Get from version control' menu,
    SELECT 'GitHub Enterprise' & TYPE your enterprise server address into server field & SELECT 'Generate Token' & SELECT 'Log in'


(NOTE: You'd have to align with GHE with the token via the browser next, accepting the default settings should be enough)

(NOTE: The authentication would also not work outside IDEA, but eh)
