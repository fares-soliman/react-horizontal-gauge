# react-horizontal-gauge

Horizontal SVG gauge component for React, inspired by [react-linear-gauge](https://github.com/moisbo/react-linear-gauge)

## Install

```
npm install react-horizontal-gauge --save
```

## Usage

```javascript
import React, { Component } from 'react';
import HorizontalGauge from 'react-horizontal-gauge';

class View extends Component {
  render() {
    return (
      <div>
        ...
        <HorizontalGauge ticks={gaugeTicks} height={70} width={500} min={0} max={10} value={7.3}/>
        ...
      </div>
    );
  }
});
```

### Props

prop      | type   | default | notes
----------|--------|---------|--------
min       | number | 0       |
max       | number | 100     |
value     | number | 0       |
width     | number | 500     | pixels
height    | number | 80      | pixels
ticks     | array  | [{label: '0', value: 0}, {label: '50', value: 50}, {label: '100', value: 100}]

## License

MIT
