# date-time

~~~~~ sh
npm install e53e04ac/date-time
~~~~~

~~~~~ mjs
import { DateTime } from 'e53e04ac/date-time';
~~~~~

~~~~~ mermaid
graph RL;
  A(["package.json"]);
  subgraph "dependencies";
    B_0(["e53e04ac/base"]);
    B_1(["e53e04ac/hold"]);
  end;
  subgraph "devDependencies";
    B_2(["@types/node"]);
  end;
  A ----> B_0;
  A ----> B_1;
  A ----> B_2;
  click B_0 "https://github.com/e53e04ac/base/tree/421cea548a7a50b26a6ada01d1d17b9a013b847c";
  click B_1 "https://github.com/e53e04ac/hold/tree/3191dd4704f3e5f90d6c27f288ede7700f5fdb66";
  click B_2 "https://www.npmjs.com/package/@types/node/v/18.14.0";
~~~~~

~~~~~ mermaid
graph RL;
  subgraph "e53e04ac/date-time";
    E_0(["DateTime"]);
  end;
  M(["index.mjs"])
  subgraph "base";
    I_0_0(["Base"]);
  end;
  subgraph "hold";
    I_1_0(["hold"]);
    I_1_1(["unwrap"]);
  end;
  M ----> I_0_0;
  M ----> I_1_0;
  M ----> I_1_1;
  E_0 ----> M;
~~~~~

~~~~~ mermaid
graph RL;
  subgraph "e53e04ac/date-time";
    E_0(["namespace DateTime"]);
    E_1(["type DateTime"]);
    E_2(["const DateTime"]);
  end;
  M(["index.d.ts"])
  subgraph "base";
    I_0_0(["Base"]);
  end;
  subgraph "hold";
    I_1_0(["Get"]);
    I_1_1(["ValueOrGet"]);
  end;
  M ----> I_0_0;
  M ----> I_1_0;
  M ----> I_1_1;
  E_0 ----> M;
  E_1 ----> M;
  E_2 ----> M;
~~~~~
