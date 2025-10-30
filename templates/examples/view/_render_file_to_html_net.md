        ```csharp {style=abap}

        // <% "{format-content-net.steps_code_comment_1}" %>
        string filePath = "input.<% get "ExampleFileExt" %>";

        // <% "{format-content-net.steps_code_comment_2}" %>
        using (Viewer viewer = new Viewer(filePath))
        {
            // <% "{format-content-net.steps_code_comment_3}" %>
            HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                
            // <% "{format-content-net.steps_code_comment_4}" %>
            viewer.View(viewOptions);
        }

        ```            