
-# IMPROVEMENTS NEED TO BE DONE 

# 🛠️ Drafted – Improvement Checklist

## 🎨 UI/UX Improvements (Design & Experience)

- [ ] **Improve Visual Hierarchy**
  - Differentiate message types using color or tags
  - Use font weights/sizes to highlight names, dates, or moods

- [ ] **Add Filters and Sorting**
  - Filter by mood (e.g., `#rant`, `#love`, `#gratitude`)
  - Sort by date or popularity (if reactions are added)

- [ ] **Search Improvements**
  - Search messages by keywords or content
  - Add live search suggestions (optional)

- [ ] **Add Reactions to Messages**
  - Allow anonymous reactions (❤️, 😆, 🙏, etc.)
  - Highlight most-reacted or trending messages

- [ ] **Responsive Design**
  - Ensure mobile-friendly layout and scaling
  - Fix spacing or wrapping issues on small screens

- [ ] **Polish UI Details**
  - Consistent spacing between cards
  - Smooth hover effects
  - Icons for music 🎵 or reaction badges

- [ ] **Daily or Random Featured Message**
  - Highlight 1–2 random or curated messages on homepage

---

## 🛠️ Functional Improvements (Spotify & Features)

- [ ] **Use Spotify API Instead of Embed Links**
  - Fetch songs using `GET /search` via Spotify Web API
  - Display song metadata (title, artist, album art, preview)

- [ ] **Add 30s Preview Playback**
  - Use `<audio>` player with `preview_url` to let users listen
  - Optional: custom JS-based play/pause button

- [ ] **Backend Token Handling**
  - Use a Node.js backend to securely retrieve Spotify access token
  - Use Client Credentials Flow (no user login required)

- [ ] **Song Selection During Message Submission**
  - Allow users to search + select a song while writing their message
  - Store the track URI or ID with the message data

- [ ] **Link to Full Song (Optional)**
  - Add a button or link to open full track in Spotify app or browser

---

## 💬 Content & Purpose Enhancements

- [ ] **Prompt Carousel on Submission Page**
  - Inspire users with prompts (e.g., “What do you regret?”, “Say thank you.”)

- [ ] **Message Categories or Moods**
  - Auto-tag messages based on content or let users pick tags

- [ ] **Anonymous Reply System (Optional)**
  - Enable replies or support messages from readers

- [ ] **Dark/Light Mode Toggle**
  - Add accessibility option for user comfort

