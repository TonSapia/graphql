#### Introduction to GraphQL

Learn about GraphQL, how it works, and how to use it. Looking for documentation on how to build a GraphQL service? There are libraries to help you implement GraphQL in many different languages. For an in-depth learning experience with practical tutorials, see How to GraphQL. Check out the free online course, Exploring GraphQL: A Query Language for APIs.

GraphQL is a query language for your API, and a server-side runtime for executing queries using a type system you define for your data. GraphQL isn't tied to any specific database or storage engine and is instead backed by your existing code and data.

A GraphQL service is created by defining types and fields on those types, then providing functions for each field on each type. For example, a GraphQL service that tells you who the logged in user is (me) as well as that user's name might look like this:

type Query {\
&nbsp; &nbsp; me:User  
\}\
\
type User {\
&nbsp; &nbsp; id:ID
\
&nbsp; &nbsp; name:String  
\}


