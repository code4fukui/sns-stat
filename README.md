# sns-stat

statcounter.com による、ソーシャルメディアのシェア変遷CSVデータ

## データ取得

```
import { CSV } from "https://js.sabae.cc/CSV.js";

const data = CSV.toJSON(await CSV.fetch("https://code4fukui.github.com/sns-stat/jp.csv"));
console.log(data);

data.sort((a, b) => {});
const latest = 
```

## データ出典

- [Social Media Stats Japan | Statcounter Global Stats](https://gs.statcounter.com/social-media-stats/all/japan#monthly-200903-202110) -> social_media-JP-monthly-200903-202110.csv -> jp.csv
- [Social Media Stats Worldwide | Statcounter Global Stats](https://gs.statcounter.com/social-media-stats#monthly-200903-202110) -> ww.csv

