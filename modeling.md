### Version 0.0.1

A very simple relationship database
- 1 category has many article 
- 1 article inside 1 category 

**Article**
- content: text
- title: string
- createdAt: datetime
- updatedAt: datetime
- deleteAt: datetime
- category_id: integer

**Category**
- name: string
- createdAt: datetime
- updatedAt: datetime
- deleteAt: datetime
