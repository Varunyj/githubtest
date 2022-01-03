# githubtest
@media (max-width: 600px) {
  .responsivetable { overflow-x: scroll;
  position: relative;
  
	  transform:scale(0.50); }
  
}


strong {
  font-weight: bold; 
}

em {
  font-style: italic; 
}

table {
  background: #f5f5f5;
  border-collapse: separate;
  box-shadow: inset 0 1px 0 #fff;
  font-size: 12px;
  line-height: 24px;
  margin: 30px auto;
  text-align: left;
  width: 800px;
  position : fixed;
} 

th {
  background:  linear-gradient(90deg,rgb(231, 66, 37), rgb(243, 35, 35));
  border-left: 1px solid #555;
  border-right: 1px solid #777;
  border-top: 1px solid #555;
  border-bottom: 1px solid #333;
  box-shadow: inset 0 1px 0 #999;
  color: #fff;
  font-weight: bold;
  padding: 10px 15px;
  position: relative;
  text-shadow: 0 1px 0 #000;  
  border-radius:3%;
}

th:after {
  background: linear-gradient(rgba(255,255,255,0), rgba(255,255,255,.08));
  content: '';
  display: block;
  height: 25%;
  left: 0;
  margin: 1px 0 0 0;
  position: absolute;
  top: 25%;
  width: 100%;
}

th:first-child {
  border-left: 1px solid #777;  
  box-shadow: inset 1px 1px 0 #999;
}

th:last-child {
  box-shadow: inset -1px 1px 0 #999;
}

td {
  border-right: 1px solid #fff;
  border-left: 1px solid #e8e8e8;
  border-top: 1px solid #fff;
  border-bottom: 1px solid #e8e8e8;
  padding: 10px 15px;
  position: relative;
  transition: all 300ms;
}

td:first-child {
  box-shadow: inset 1px 0 0 #fff;
} 

td:last-child {
  border-right: 1px solid #e8e8e8;
  box-shadow: inset -1px 0 0 #fff;
} 

tr:last-of-type td {
  box-shadow: inset 0 -1px 0 #fff; 
}

tr:last-of-type td:first-child {
  box-shadow: inset 1px -1px 0 #fff;
} 

tr:last-of-type td:last-child {
  box-shadow: inset -1px -1px 0 #fff;
} 

tbody:hover td {
  color: transparent;
  text-shadow: 0 0 3px #aaa;
}

tbody:hover tr:hover td {
  color: #444;
  text-shadow: 0 1px 0 #fff;
}

.root {
  margin-left: 34%;
}

.col {
  margin-left: -0.75rem;
  margin-right: -0.75rem;
}

.row .col.s1 {
  width: 8.3333333333%;
  margin-left: auto;
  left: auto;
  right: auto;
}

.row .col.s2 {
  width: 16.6666666667%;
  margin-left: auto;
  left: auto;
  right: auto;
}

.row .col.s3 {
  width: 25%;
  margin-left: auto;
  left: auto;
  right: auto;
}

.row .col.s4 {
  width: 33.3333333333%;
  margin-left: auto;
  left: auto;
  right: auto;
}

.row .col.s5 {
  width: 41.6666666667%;
  margin-left: auto;
  left: auto;
  right: auto;
}

.row .col.s6 {
  width: 50%;
  margin-left: auto;
  left: auto;
  right: auto;
}

.row .col.s7 {
  width: 58.3333333333%;
  margin-left: auto;
  left: auto;
  right: auto;
}

.row .col.s8 {
  width: 66.6666666667%;
  margin-left: auto;
  left: auto;
  right: auto;
}

.row .col.s9 {
  width: 75%;
  margin-left: auto;
  left: auto;
  right: auto;
}

.row .col.s10 {
  width: 83.3333333333%;
  margin-left: auto;
  left: auto;
  right: auto;
}

.row .col.s11 {
  width: 91.6666666667%;
  margin-left: auto;
  left: auto;
  right: auto;
}

.row .col.s12 {
  width: 100%;
  margin-left: auto;
  left: auto;
  right: auto;
}




.tabs {
  position: relative;
  overflow-x: auto;
  overflow-y: hidden;
  height: 48px;
  width: 100%;
  background-color: #fff;
  margin: 0 auto;
  white-space: nowrap;
}

.tabs.tabs-transparent {
  background-color: transparent;
}

.tabs.tabs-transparent.a
.tabs.tabs-transparent .tab.disabled a,
.tabs.tabs-transparent .tab.disabled a:hover {
  color: rgba(255, 255, 255, 0.7);
}

.tabs.tabs-transparent .tab a:hover,
.tabs.tabs-transparent .tab a.active {
  color: #fff;
}

.tabs.tabs-transparent .indicator {
  background-color: #fff;
}

.tabs.tabs-fixed-width {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}

.tabs.tabs-fixed-width .tab {
  -webkit-box-flex: 1;
  -webkit-flex-grow: 1;
      -ms-flex-positive: 1;
          flex-grow: 1;
}

.tabs .tab {
  display: inline-block;
  text-align: center;
  line-height: 48px;
  height: 48px;
  padding: 0;
  margin: 0;
  text-transform: uppercase;
}

.tabs .tab a {
  color: rgba(238, 110, 115, 0.7);
  display: block;
  width: 100%;
  height: 100%;
  padding: 0 24px;
  font-size: 14px;
  text-overflow: ellipsis;
  overflow: hidden;
  -webkit-transition: color .28s ease, background-color .28s ease;
  transition: color .28s ease, background-color .28s ease;
}

.tabs .tab a:focus, .tabs .tab a:focus.active {
  background-color: rgba(246, 178, 181, 0.2);
  outline: none;
}

.tabs .tab a:hover, .tabs .tab a.active {
  background-color: transparent;
  color: #ee6e73;
}

.tabs .tab.disabled a,
.tabs .tab.disabled a:hover {
  color: rgba(238, 110, 115, 0.4);
  cursor: default;
}

.tabs .indicator {
  position: absolute;
  bottom: 0;
  height: 2px;
  background-color: #f6b2b5;
  will-change: left, right;
}

@media only screen and (max-width: 992px) {
  .tabs {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
  }
  .tabs .tab {
    -webkit-box-flex: 1;
    -webkit-flex-grow: 1;
        -ms-flex-positive: 1;
            flex-grow: 1;
  }
  .tabs .tab a {
    padding: 0 12px;
  }
}
