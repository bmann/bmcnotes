- Reading
	- {{query (and (page-property tags book) (page-property tags reading))}}
	  query-properties:: [:page :author :link :book-cover]
- To Read
	- {{query (and (page-property tags book) (page-property tags toread))}}
	  query-properties:: [:page :author]
- Completed
	- {{query (and (page-property tags book) (page-property tags completed))}}
	  query-properties:: [:page :author :link :book-cover]
-