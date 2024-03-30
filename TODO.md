parser.rs::11 find a way to remove all whitespaces

-   get user input via cli once the engine is started
-   parse create table and insert statements
-   implement io engine
-   indices
    -   B-Tree
    -   each leaf node points to a data page (fixed size 16kB used by InnoDB by mySQL)
    -   separate files for indices
-   basic constraints

-   limitations:
    -   I don't handle the case that a single record exceeds the size of a datapage
    -   I don't implement DB metadata, such as users or privileges