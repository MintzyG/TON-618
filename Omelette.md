#MissingFeatures 
# Missing Features
- [ ] Implement on routes GetByID, Update e Delete, multiple route handling because we expect different behaviour if handler is reached through different routes like /list/{id} or /omelette/{id}/list/{list_id}
- [ ] Optimize route access for omelette
# Bugs
- [ ] When patching lists and cards, swapping positions doesn't swap the position of other cards as it should do
- [ ] Position should be also updated when deleting a card or list
- [ ] Certain routes should not return the entire table, for example, patch table return the table with its lists and cards, it should not be that way, implement a function, queryWithChildren