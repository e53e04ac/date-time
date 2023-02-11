# date-time

~~~~~ sh
npm install e53e04ac/date-time
~~~~~

~~~~~ mjs
import { DateTime } from 'e53e04ac/date-time';
~~~~~

~~~~~ mermaid
graph LR;
  A(["date-time"]);
  B0(["e53e04ac/base"]);
  B1(["e53e04ac/hold"]);
  C0(["@types/node"]);
  click B0 href "https://github.com/e53e04ac/base";
  click B1 href "https://github.com/e53e04ac/hold";
  subgraph "e53e04ac/date-time";
    A;
  end;
  subgraph "dependencies";
    B0 --import--> A;
    B1 --import--> A;
  end;
  subgraph "devDependencies";
    C0 --import--> A;
  end;
~~~~~
