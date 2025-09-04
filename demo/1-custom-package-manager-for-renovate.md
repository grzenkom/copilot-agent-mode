# Custom package manager for Renovate

```text
I use the Renovate bot to get automated updates for project dependencies.
Out of the box, it does not support DBT dependencies, but it is possible
to define custom managers.

Use #context7 to get information about custom data sources and data managers
in Renovate as well as the JSONata query and transformation language.

#fetch https://hub.getdbt.com/api/v1/metaplane/dbt_expectations.json
with an example feed of updates for a DBT package.

Write JSONata rule to transform the JSON file to the required format
and test it with the `jsonata` tool installed locally.
```

## Links

- https://docs.renovatebot.com/modules/datasource/custom/#usage
- https://try.jsonata.org/
