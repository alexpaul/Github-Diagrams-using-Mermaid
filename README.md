## Include diagrams in your Markdown files with Mermaid

```mermaid
flowchart TD 
  A[Deploy to production] ---> B{Is it Friday?};
  B -- Yes --> C[Do not deploy!];
  B -- No --> D[Run deploy.sh to deploy!];
  C ----> E[Enjoy your weekend!];
  D ----> E[Enjoy your weekend!];
```

## Resource 

* [Include diagrams in your Markdown files with Mermaid](https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/)
