# api_yatube
api_yatube
***
##Привет
###Привет
```python
def perform_update(self, serializer):
    if serializer.instance.author != self.request.user:
        raise PermissionDenied('Изменение чужого контента запрещено!')
    super(CommentViewSet, self).perform_update(serializer)


def perform_destroy(self, serializer):
    if serializer.instance.author != self.request.user:
        raise PermissionDenied('Изменение чужого контента запрещено!')
    super(CommentViewSet, self).perform_destroy(serializer)
 ```
* Привет
* Привет 
