# Esquema GraphQL

type Usuario {
 id: ID
 nombre: String
 email: String
}

type Query {
 usuarios: [Usuario]
 usuario(id: ID): Usuario
}

type Mutation {
 crearUsuario(nombre: String, email: String): Usuario
}
