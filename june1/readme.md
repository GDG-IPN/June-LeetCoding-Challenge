
``` Python
# Solución usando recursión
class Solution:
    def invertTree(self, root):
        if(root):
            root.left, root.right = (
                self.invertTree(root.right), 
                self.invertTree(root.left)
            )
        return root
```

``` Python
# Solución usando una stack
class Solution:
    def invertTree(self, root):

```

``` Python
# Solución usando una queue
class Solution:
    def invertTree(self, root):

```
