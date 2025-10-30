        ```java {style=abap}

        // <% "{format-content-java.steps_code_comment_1}" %>
        String filePath = "input.<% get "ExampleFileExt" %>";

        // <% "{format-content-java.steps_code_comment_2}" %>
        try (Viewer viewer = new Viewer(filePath))
        {
            // <% "{format-content-java.steps_code_comment_3}" %>
            HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                
            // <% "{format-content-java.steps_code_comment_4}" %>
            viewer.view(viewOptions);
        }

        ```
            