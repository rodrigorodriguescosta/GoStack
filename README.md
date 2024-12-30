# GoStack

GoStack is a lightweight and extensible framework for building APIs in Go, combining the power of gRPC and REST. It is designed to be framework-agnostic, allowing developers to use their preferred web server or easily switch between them with minimal effort. GoStack simplifies API development with reusable modules, middleware integration, and standard handlers.

---

## Key Features

### 1. **gRPC and REST APIs**
- Use Protocol Buffers (Protobuf) to define APIs that can seamlessly work with both gRPC and REST.
- Generate client and server code for multiple languages, reducing boilerplate and improving consistency.

### 2. **Framework-Agnostic Design**
- Supports web servers like [Fiber](https://gofiber.io/) and [Gin](https://gin-gonic.com/) out of the box.
- Easily extendable to other frameworks with a simple interface implementation.

### 3. **Standard Handlers**
- Built-in standard handlers to speed up development.
- Handle common tasks consistently across your applications.

### 4. **Middleware Integration**
- Simplified process to add middleware for logging, authentication, rate-limiting, etc.
- Middleware can be customized and shared across projects.

### 5. **Reusable Apps/Modules**
- Create modular, reusable components that can be easily integrated into multiple projects.
- Add or remove apps from your project with minimal configuration.

### 6. **Existing Code Compatibility**
- Integrate with existing Go projects by implementing a simple interface.

---

## Why Protobuf?

Protobuf enables powerful and flexible API development by:

- **Dual Protocol Support**: Write your API once and use it for both gRPC and REST communication.
- **Code Generation**: Automatically generate code for various languages, reducing boilerplate and ensuring consistency.
- **Documentation Support**: Simplify API documentation generation.
- **Future-Proofing**: Keep your API framework-independent with minimal effort to switch.

---

## How It Works

### Adding a Web Server
Choose your preferred web server (e.g., Fiber, Gin). Switching frameworks is as simple as updating one line of code.

### Creating Apps/Modules
Organize your project into reusable apps/modules. Each app can:
- Define its own routes and handlers.
- Be shared across multiple projects by adding it to the framework configuration.

### Middleware
Add custom or standard middleware to your project. Use it for:
- Logging
- Authentication
- Error Handling
- And more!

---

## Getting Started

### Installation
```bash
go get github.com/rodrigorodriguescosta/gostack
```

### Example Usage

#### Initialize a Project
```go


}
```

#### Create a Module
```go

```

---

## Contributing
We welcome contributions! Please check out our [Contributing Guidelines](CONTRIBUTING.md) for more information.

---

## License
This project is licensed under the [MIT License](LICENSE).

