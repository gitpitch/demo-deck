@title[Live Code Presenting]

@snap[north span-50 text-center]
@fa[search-plus text-pink]
@snapend

@snap[midpoint span-100 text-center]
GitPitch Live Code Presenting lets you
**Step-and-ZOOM** into Source Code on any Slide
@snapend

@snap[south span-50 text-center]
@fa[code fa-5x]
@snapend

---
@title[Live Code Presenting Demo]

@snap[north span-100 text-center text-smallcaps text-08]
Live Code Presenting
@snapend

```sql zoom-19
CREATE TABLE "topic" (
    "id" serial NOT NULL PRIMARY KEY,
    "forum_id" integer NOT NULL,
    "subject" varchar(255) NOT NULL
);

ALTER TABLE "topic"
ADD CONSTRAINT forum_id

FOREIGN KEY ("forum_id")
REFERENCES "forum" ("id");
```

@snap[south span-100 text-08]
@[1-5](Step-into and focus on specific lines of code on any slide.)
@[2-4, zoom-09](Zoom in-or-out to help guide your audience.)
@[6-9, zoom-14](Using optional annotations &#40; like this one &#41; for extra context.)
@snapend
