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
* [Mermaid Live Editor](https://mermaid-js.github.io/mermaid-live-editor/edit#pako:eNpVkM-KwkAMxl8l5OSCfYEeBG3Vi6Cgt46H0InOIPOHdMoibd99p5aF3ZyS7_t9IWTANmjGEp9C0cCtVh5ybZvKiO2So-4ORbEZj5zABc_vEXarY4DOhBitf34t_G6GoBpOM8aQjPWvabGqT_7seYS6OVFMId7_OrfvMMK-sReT1_93jHBOHZoHlQ8qWhKoSD4IrtGxOLI6nz7MisJk2LHCMrea5KVQ-SlzfdSUeK9tCoJlkp7XSH0K17dvf-eFqS3lL7hFnH4ABg5bBA)
