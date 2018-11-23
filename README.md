# best-article-spinner
Paraphrasing sends articles, essays or other written works. A.K.A. article spinner.

After investigating many article spinners, I have found one that produces the most complete content of all and makes an API wrapper for that.

## Usage
`$ git clone https://github.com/fotostocks/best-article-spinner.git`

`$ cd article-rewriter-api`

`$ composer install`

Request must be in `application/json`

Example `POST` request to `http://yourawesomehost.com/article-rewriter-api/rewrite` with the text you want to check:
```json
{
    "text":"My pleasure John. Please spread the news about the list through an independent bookstore. I know
that many independent book stores have blogs or websites. Thank you for your review of Indie books.
What do you think about that amazing trip?",
    "include_capitalized": true
}
```

Example `JSON` response:
```json
{
    "success": true,
    "message": "Text rewritten successfully",
    "data": {
        "rewritten_text": "My pleasure John. Please post the news on the list through an independent bookstore. I know
that many independent bookstores have blogs or websites. Thank you for your review of independent books.
What do you think of this incredible journey?"
    }
}
```

### Note
Use this at your own risk, because it depends on third parties. Also consider using a proxy.

best-spinner.com
[Best free article rewriter and spinner](https://best-spinner.com)

