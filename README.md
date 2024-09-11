**Manual RSS Feed** provides two clips to manually create and add to an RSS **XML** file.

## Clips

| Title         | Description 						      |
| ---           | ---                                     |
| **RSS Feed**  | Adds the framework of the RSS feed      |
| **RSS Item**  | Adds an RSS item to an extant feed file |

## Details

* Any dates are in the following format: `%a, %d %b %Y %H:%M:%S -[UTC offset]`

	For example, the time of writing this README update would be `Tue, 10 Sep 2024 22:17:00 -0700`, with `-0700` the UTC offset for Pacific Daylight Time. During Pacific Standard Time, the UTC offset would be `-0800`.
	
	[strfti.me](https://www.strfti.me/?f=%25a%2C+%25d+%25b+%25Y+%25H%3A%25M%3A%25S) can show you how it will look.

* The **RSS Item** clip goes between `</ttl>` and `</channel>`. Use an **RSS Item** clip for each item in the RSS feed.

* If you want to include links and/or images in the `description` of an **RSS Item**, you need to use HTML entitles for angle brackets and quotes. For quick reference:
	* `<` = `&lt;`
	* `>` = `&gt;`
	* `"` = `&quot;`