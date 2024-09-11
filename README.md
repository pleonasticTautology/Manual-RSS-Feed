**Manual RSS Feed** provides two clips to manually create and add to an RSS **XML** file.

## Clips

| Title         | Description 						      |
| ---           | ---                                     |
| **RSS Feed**  | Adds the framework of the RSS feed      |
| **RSS Item**  | Adds an RSS item to an extant feed file |

## Details

* Any dates are in the following format: `%a, %d %b %Y %H:%M:%S -[UTC offset]`

	For example, the time of writing this README update would be `Tue, 10 Sep 2024 22:17:00 -0700`, with `-0700` the UTC offset for Pacific Daylight Time. During Pacific Standard Time, the UTC offset would be `-0800`.

* The default value for `<ttl>` is `20000` minutes.

* The **RSS Item** clip goes between `</ttl>` and `</channel>`. Use an **RSS Item** clip for each item in the RSS feed.