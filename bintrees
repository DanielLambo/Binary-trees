class Node:
    def __init__(self, key):
        self.key = key
        self.left = None
        self.right = None

    def inorder_traversal(self):
        if self.left:
            self.left.inorder_traversal()
        print(self.key, end=" ")
        if self.right:
            self.right.inorder_traversal()

    def preorder_traversal(self):
        print(self.key, end=" ")
        if self.left:
            self.left.preorder_traversal()
        if self.right:
            self.right.preorder_traversal()
            
    def postorder_traversal(self):
        if self.left:
            self.left.postorder_traversal()
        if self.right:
            self.right.postorder_traversal()
        print(self.key, end = " ")
        
# Example usage:
root = Node(1)
root.left = Node(2)
root.right = Node(3)
root.left.left = Node(4)
root.left.right = Node(5)

print("Inorder Traversal:")
root.inorder_traversal()

print("\nPreorder Traversal:")
root.preorder_traversal()

print("\nPostorder Traversal:")
root.postorder_traversal()

