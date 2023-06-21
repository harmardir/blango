# blango

## Generic Relationships

- contenttypes framework keeps track of all models installed in a Django project.
- ` python3 manage.py shell `
- ` from django.contrib.contenttypes.models import ContentType `
- A foreign key specifies a relationship between a class and a single model.
- A generic foreign key specifies a relationship between a class and many different models.
- Using GenericRelation indicates a reverse generic relationship.
- Using GenericForeignKey indicates a generic relationship.
