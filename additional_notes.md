## What about Unicode characters? Why only printable ASCII?
For UTF-8, ASCII characters take up 1 byte each but other characters take multiple. Additionally, it complicates the implementation (note that case detection already requires costumes for each character). 

Are the characters as widely supported? There is an increased risk of places that will disallow or handle them wrong. 

These issues significantly outweigh any possible benefit.