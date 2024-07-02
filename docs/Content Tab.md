# Content Tabs
Sometimes, it's desirable to group alternative content under different tabs,e.g. when describing how to access an API from different languages or environments. Materials for MKdocs allows for beautiful and functional tab, grouping code blocks and other content.
### Grouping Code blocks
Code blocks are one of the primary targets to be grouped, and can be considered a special case of content tabs, as tabs with a single code block are always rendered without horizontal spacing:
=== "C"

    ``` c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```

=== "C++"

    ``` c++
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```

