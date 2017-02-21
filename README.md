Key for graphs:
- oval is human step/signoff
  - todo - label or colour code human tasks with relman/releng/qa/other
- box is automation

Initial setup:
  virtualenv playpit
  . playpit/bin/activate
  pip install -e git+https://github.com/ninowalker/ymlgraph.git#egg=yamlgraph

Generate svg:
  ymlgraph --format svg <file>
