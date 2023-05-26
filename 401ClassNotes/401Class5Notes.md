# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: Implementation: Linked Lists

Given that we are going to need to be familiar with the Sequelize documentation, I thought it would be nice to have direct links to some of the common areas we will be using and this is something that I can continue to update as we get more experience!

The examples below will require express and router to be imported as well as a working model(with schema) to create or update.

```javascript
const express = require('express');
const router = express.Router();
```

- POST : (create an entry) [Create Method](https://sequelize.org/docs/v6/core-concepts/model-instances/#a-very-useful-shortcut-the-create-method)

```javascript
router.post('/something', async (req, res) => {
  let newSomething = await somethingModel.create(req.body);

  res.status(200).send(newSomething);
});
```

- GET : (all) [Simple Select Queries](https://sequelize.org/docs/v6/core-concepts/model-querying-basics/#simple-select-queries)

```javascript
router.get('/something', async (req, res) => {
  let allSomethingEntries = await somethingModel.findAll();
  
  res.status(200).send(allSomethingEntries);
});
```

- GET : (one entry) [Simple Select Queries](https://sequelize.org/docs/v6/core-concepts/model-querying-basics/#simple-select-queries)

```javascript
router.get('/something/:id', async (req, res) => {
  let singleSomething = await somethingModel.findAll({ where: { id: req.params.id } });
  
  if (singleSomething === null) {
    console.log('something item not found!');
  } else {
    res.status(200).send(singleSomething);
  }
});
```

- PUT : (update one entry) [Simple Update Queries](https://sequelize.org/docs/v6/core-concepts/model-querying-basics/#simple-update-queries)

```javascript
router.put('/something/:id', async (req, res) => {
  await somethingModel.update(req.body, {
    where: {
      id: req.params.id,
    },
  });
  let updatedSomething = await somethingModel.findAll({ where: { id: req.params.id } });
  res.status(200).send(updatedSomething);
});
```

- DELETE : (delete one entry) [Simple Delete Queries](https://sequelize.org/docs/v6/core-concepts/model-querying-basics/#simple-delete-queries)

```javascript
router.delete('/something/:id', async (req, res) => {
  let id = parseInt(req.params.id);
  await somethingModel.destroy({
    where: {
      id,
    },
  });

  res.status(200).send('something item selected was deleted!');
});
```

## Resources

[Big O: Analysis of Algorithm Efficiency](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/big_oh.html)

[Linked Lists](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)

[What's a Linked List, Anyway pt.1](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)

[What's a Linked List, Anyway pt.2](https://medium.com/basecs/whats-a-linked-list-anyway-part-2-131d96f71996)

## Class Notes

## Things I want to know more about
