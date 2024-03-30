# H1
## H2
### H3
#### H4
##### H5
###### H6

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

```
import 'package:flutter/material.dart';

class ScoreCard extends StatelessWidget {
  const ScoreCard({
    super.key,
    required this.score,
  });

  final ValueNotifier<int> score;

  @override
  Widget build(BuildContext context) {
    return ValueListenableBuilder<int>(
      valueListenable: score,
      builder: (context, score, _) {
        return Padding(
          padding: const EdgeInsets.fromLTRB(12, 6, 12, 18),
          child: Text(
            'Score: $score'.toUpperCase(),
            style: Theme.of(context).textTheme.titleLarge!,
          ),
        );
      },
    );
  }
}

```

- [ ] item 1
- [ ] item 2
- [ ] item 3
- [ ] item 4
- [ ] item 5
      
