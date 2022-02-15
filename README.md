## Include diagrams in your Markdown files with Mermaid

## Example 1
```mermaid
flowchart TD 
  A[Deploy to production] ---> B{Is it Friday?};
  B -- Yes --> C[Do not deploy!];
  B -- No --> D[Run deploy.sh to deploy!];
  C ----> E[Enjoy your weekend!];
  D ----> E[Enjoy your weekend!];
```

## Example 2
```mermaid
flowchart TD
  8 --> 3; 
  8 --> 10; 
  3 --> 1; 
  3 --> 6; 
  6 --> 4; 
  6 --> 7;
  10 --> 11;
  10 --> 14;
  14 --> 13;
  14 --> 19;
```

***

## Example 3

```mermaid
journey
    title My working day
    section Go to work
      Make tea: 5: Me
      Go upstairs: 3: Me
      Do work: 1: Me, Cat
    section Go home
      Go downstairs: 5: Me
      Sit down: 5: Me
```

***

## Resource 

* [Github Blog - Include diagrams in your Markdown files with Mermaid](https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/)
* [Mermaid Docs](https://mermaid-js.github.io/mermaid/#/)
