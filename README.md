# servlet
To move a Murach book example to OpenShift

```
mkdir src/main
mv src/java src/main
mv src/web src/main/webapp

$ tree
.
├── pom.xml
├── README.md
└── src
    ├── conf
    │   └── MANIFEST.MF
    └── main
        ├── java
        │   └── murach
        │       ├── business
        │       │   └── User.java
        │       ├── data
        │       │   └── UserDB.java
        │       └── email
        │           └── EmailListServlet.java
        └── webapp
            ├── index.html
            ├── META-INF
            │   └── context.xml
            ├── styles
            │   └── main.css
            ├── thanks.jsp
            └── WEB-INF
                └── web.xml
```

