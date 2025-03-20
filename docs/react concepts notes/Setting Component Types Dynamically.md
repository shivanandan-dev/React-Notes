 ## Setting Component Types Dynamically
 - The Component allows you to dynamically set the type of container element it renders based on the containerType prop. This enables more flexible and reusable components since the container type can be specified at runtime.

    ```jsx
    function Component({containertype, children}) {
        const ContainerType = containerType

        return (
            <>
                <ContainerType>
                    {children}
                </ContainerType>
            </>
        )
    }

    function App() {
        return (
            <>
                <Component containerType = "div">Hello, World!</Component>
                <Component containerType = "section">Hi, Shiva!</Component>
            </>
        )
    }
    ```
- Can use directly without assigning to a variable by making the prop name's starting index to be in upper case. Ex: `ContainerType`