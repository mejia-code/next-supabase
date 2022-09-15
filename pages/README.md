# full-stack

This example uses NextJS React, Tailwind and Supabase

## Getting Started

[How to Build a Full Stack Application With Supabase, React, and Tailwind CSS in Nextjs](https://www.freecodecamp.org/news/how-to-build-a-full-stack-application-with-tailwind-css-and-supabase-in-nextjs/)

## Step 1: supabase

```bash
npm install @supabase/supabase-js
```

```bash
npm install -D tailwindcss
```

cd to your project

```bash
npx tailwindcss init
```

```bash
npm install @supabase/supabase-js
npx create-next-app --e with-tailwindcss project_db
cd project_db
pnpm run dev
```

where proyect_db is the name of the project

## Step 2: frontend

# Terminology

1. async function: a function that returns a promise and can be awaited on. For example, a function that makes a network request to an API.

1. Promise is an object that represents the eventual completion or failure of an asynchronous operation. A promise is in one of these states:

   - pending: initial state, neither fulfilled nor rejected.
   - fulfilled: meaning that the operation was completed successfully.
   - rejected: meaning that the operation failed.

1. PostgreSQL is a relational database management system (RDBMS) based on SQL (Structured Query Language), the standard language for relational database management.

1. A relational database is a type of database that stores and provides access to data points that are related to one another. Relational databases are based on the relational model, an intuitive, straightforward way of representing data in tables. Each row in the table is a record with a unique ID called the key. The columns of the table hold attributes of the data, and each record usually has a value for each attribute, making it easy to establish the relationships among data points.

1. RLS (Row Level Security) is a feature of PostgreSQL that allows you to restrict access to rows in a table based on the user's identity. This is useful for multi-tenant applications where you want to restrict access to data based on the user's organization.

1. multi-tenant application: a software application that is designed to serve multiple tenants (users, customer companies, organizations, etc.) using a single instance of the application software.

1. Choose a default types in PostgreSQL. List of [data type](https://www.postgresql.org/docs/9.1/datatype.html) options.

1. Difference between a relational database and a non-relational database. [Relational vs. Non-Relational Databases](https://www.mongodb.com/nosql-explained/relational-vs-non-relational-databases)

   > Relational databases are based on the relational model, an intuitive, straightforward way of representing data in tables. Each row in the table is a record with a unique ID called the key. The columns of the table hold attributes of the data, and each record usually has a value for each attribute, making it easy to establish the relationships among data points.
   > Mathematically, it is an algebraic structure with sets, elements and boolean set operations. Geometrically, you can think of it as a tree.
   > Relational in this case does not mean a realational graph.
   > A relational graph allows other operations: merges and splits.
   > the multiple edges between two nodes or the multiple nodes between two edges.

1. [Join Relationships and JOINing in SQL](https://dataschool.com/learn-sql/joins/). A join is a way to combine rows from two or more tables, based on a related column between them. This allows for many-to-many relationships to be represented in a single table.

1. Default values in PostgreSQL. [Default Values](https://www.postgresql.org/docs/9.1/ddl-default.html)

- null value is a value in a field that has been left blank. A field with a null value is a field with no value.
- Empty string is a string with no characters. It is different from a null value. An empty string is still a value. It is just a value with no data.
- use Null when dealing with numbers, dates, or other data types. for example, you might want to perform count operations on the data and not count or add the values of null fields. specially addition ops.

1. composite primary key in supabase is a combination of two or more columns that uniquely identify each row in a table. [Composite Primary Key](https://www.postgresqltutorial.com/postgresql-composite-primary-key/)

1. In Extra options:

   - Is Identity, meaning that the column is an auto-incrementing integer. This is useful for primary keys.

   - define as array: use to define your column as a variable-length multidimensional array.

   - is nullable: use to define your column as nullable.
     > - Array:
     >   [1, 2, 3, ...] a data structure with ordered elements. The elements can be accessed by their index. The 1st element is at index 0. The last element is at index length of the array minus 1.

   > - For all $i$ in $I$, there is a unique $a$ in $A$ such that $a = A[i]$ and $i = \{0, 1, 2, ..., lenght_{array} -1\}$

1. Extra options
   Id: Is Identity
   name: and the rest of the columns are nullable

   - is unique ma

1. `npm add @supabase/supabase-js` makes the connection to the database and the frontend to the backend.

1. cd to directory and run `npm run dev` to start the server.

```bash
 cd project_db
```

1. `npm run dev` to run the project

```bash
  pnpm run dev
```

# Sum-post: [wip] 👇🏾

### Relational graph vs relational database

🧶multiple edges between two nodes or multiple nodes between two edges, 🧶 many-to-many relationships, 🧶 split or merges describe a relational graph, not a relational db
🌳 relational db: a tree, sets, elements, boolean ops

#graphtheory #supabase #PostgreSQL #SQL

### Null vs empty string
