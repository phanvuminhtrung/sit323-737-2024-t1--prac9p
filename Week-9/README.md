## TASK
- Install MongoDB into the Kubernetes cluster, either as a standalone instance or a replica set,
depending on your requirements.
- Create a MongoDB user with appropriate permissions for your application.
- Configure persistent storage for the MongoDB database by creating a Persistent Volume and
Persistent Volume Claim.
- Create a Kubernetes Secret for the MongoDB user credentials and add them to the deployment
manifest.
- Modify the Kubernetes deployment manifest for your application to include the newly added
MongoDB database. Ensure that the configuration includes information such as the database
type, credentials, and other necessary parameters.
- Test the deployment to ensure that the application can connect to the MongoDB database and
perform basic CRUD (Create, Read, Update, Delete) operations.

## OUTLINE FILES

### createConfigMap.yaml

This file is used to create a ConfigMap in Kubernetes. ConfigMaps allow you to decouple configuration artifacts from image content to keep containerized applications portable.

### createHeadlessService.yaml

This file is used to create a headless service in Kubernetes. A headless service is used when you don't need load-balancing and want to directly reach the pods.

### createMongoDbSecret.yaml

This file is used to create a Secret in Kubernetes that holds the credentials for accessing your MongoDB instance.

### createPersistentVolumeClaim.yaml

This file is used to create a Persistent Volume Claim (PVC) in Kubernetes. PVCs are a way for consumers (pods) to request a specific size and access mode for storage (Persistent Volume) that can persist beyond the life of a pod.

### createStatefulSet.yaml

This file is used to create a StatefulSet in Kubernetes. StatefulSets are used for applications that require stable network identifiers, stable persistent storage, and ordered, graceful deployment and scaling.

### createStorageClass.yaml

This file is used to create a StorageClass in Kubernetes. StorageClasses provide a way for administrators to describe the "classes" of storage they offer.

To apply these configurations, use the command `kubectl apply -f <filename>`.

## TEST ON TERMINAL:
![test](https://github.com/phanvuminhtrung/sit323-737-2024-t1--prac9p/assets/63788637/e80b0b28-332e-459c-80ea-3d2b8098f595)

