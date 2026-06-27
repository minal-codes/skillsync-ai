# Database Collections

## users

- uid
- fullName
- email
- profileImage
- bio
- college
- github
- linkedin
- skillsTeach[]
- skillsLearn[]
- availability
- xp
- level
- badges[]
- createdAt

---

## swapRequests

- requestId
- senderId
- receiverId
- skillOffered
- skillRequested
- status
- createdAt

---

## chats

- chatId
- participants[]
- lastMessage
- updatedAt

---

## messages

- messageId
- chatId
- senderId
- text
- timestamp

---

## sessions

- sessionId
- mentorId
- learnerId
- topic
- date
- status

---

## notifications

- notificationId
- userId
- title
- message
- isRead

---

## aiMatches

- matchId
- userA
- userB
- score
- explanation
- learningContract