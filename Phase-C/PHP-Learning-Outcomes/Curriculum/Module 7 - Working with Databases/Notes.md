## Suggestions

### Knowledge Units

- The difference between query bindings and prepared statements [Stackoverflow Convo](http://stackoverflow.com/questions/16128005/codeigniter-db-class-vs-prepared-statements)

### Behavior

- Use `IN` as opposed to multiple `OR` with complex queries

eg SELECT * FROM `NORA` WHERE name = 'nora' OR uname =  'nora' AND ...

SELECT * FROM `NORA` WHERE 'nora' IN ('awesome', 'great')
