## 3.1


There are **4 models** in this scene:

1. Cylinder - it's the tree's trunk
2. Cone - it's the tree's leaves
3. PlaneHelper - helps visualizing the rotation around the center of the scene on the yy axis
4. AxesHelper - helps visualizing the axes in the center of the scene

The Cylinder and the Cone make up the Tree, they are put in a Tree Group, and the group is returned:

```javascript
			// Tree

			const tree = new THREE.Group();

			tree.add(cylinder);

			tree.add(cone);

			return tree;
```

![alt text](ezgif-83a73e24169db9.gif)

Trees with simple linear movement