# COMP551: Applied Machine Learning (Fall 2020)
instructor: Siamak Ravanbakhsh

I'll use this repository to share the code for some of the topics that we cover in the class. 
If you have trouble following parts of the code:
* first try to research and find an answer on your own
* discuss with your classmates in the forum in myCourses
* use TA and Instructor office hours to ask your questions

---

To run this repository within a docker container, run the following command from the root of this project.

```
docker run -d -p 8080:8080 --name "ml-workspace" -v "${PWD}:/workspace" --shm-size 512m --restart always mltooling/ml-workspace:latest
```

The notebook should now be accessible from [localhost:8080](http://localhost:8080/).