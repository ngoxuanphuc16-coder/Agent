# /find — Natural Language Search

## Trigger
"tìm" | "tìm kiếm" | "find" | "có gì về"

## Steps
1. Parse câu hỏi → xác định filter (type/date/status/tag/keyword)
2. Nếu là câu hỏi KIẾN THỨC → route sang 02_Knowledge với skill wiki-query
3. Nếu là tìm FILE → grep trong 00_LIFE theo filter
4. Trả kết quả có path + frontmatter tóm tắt

