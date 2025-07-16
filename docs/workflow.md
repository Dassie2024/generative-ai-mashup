# 🎼 Generative AI Mashup Workflow


## Use Case Description

The goal was to use a generative AI tool to blend vocal and instrumental components into a cohesive, original composition. I used [Fadr.com](https://fadr.com/stems), a free stem separation platform that lets users isolate vocals and instrumentals with just a few clicks.

Fadr isn’t just a tool—it’s a bridge between music and machine. With intuitive UI and powerful AI models, it enables musicians to remix, experiment, and reimagine sound. For me, it became the perfect partner on this journey, merging my love of music tech with hands-on creative exploration.

---

## Why I Chose Fadr

- **User-friendly interface**
- **Accurate, fast stem separation**
- **Displays key and BPM for easy remix planning**
- **Free unlimited uploads (unlike many competitors)**

Other platforms like voice.ai and moises.ai limit uploads or require payment. Fadr gave me the creative freedom I needed to explore and iterate.

---

## Tools Used

- **Fadr.com** – for stem separation
- **Pro Tools** – for pitch/tempo adjustment and mixing
- **songkeyfinder.com** – to identify keys for harmonic compatibility

---

## Step-by-Step Workflow

### 1. **Choose Songs**
- Select two tracks for the mashup.
- Optionally, use [songkeyfinder.com](https://songkeyfinder.com) to identify the key and BPM.

### 2. **Download Audio**
- Find and download MP3 versions of both songs (for educational use).

### 3. **Separate Stems Using Fadr**
- Go to [fadr.com/stems](https://fadr.com/stems).
- Upload both songs.
- Fadr will automatically detect and display the key + BPM.
- Download your desired **instrumental** and **vocal** stems as MP3 files.

### 4. **Import Stems into Pro Tools**
- Create a new session.
- Import all vocal and instrumental stem files.

### 5. **Organize Tracks**
- Solo and audition the stems you want to use.
- Move selected tracks into a new folder/session for editing.

### 6. **Pitch Adjustment**
- Change the pitch of the instrumental stem to match the vocal track’s key.
- In Pro Tools:
  - Select the track
  - Set it to *Polyphonic*
  - Right-click > *Elastic Properties* > Adjust pitch (in semitones)

### 7. **Edit Audio Start Points**
- Use **tap-to-transient** to find the first beat of each track.
- Crop the tracks so they start cleanly on beat 1.

### 8. **Adjust Tempos**
- Align the BPM of both tracks.
- In Pro Tools:
  - Convert tracks to *tick-based*
  - Use Elastic Audio (Polyphonic)
  - Adjust tempo in the timeline to match beat alignment

### 9. **Blend and Mix**
- Layer the adjusted instrumental and vocal stems.
- Balance levels, add fades, and adjust EQ if needed.

### 10. **Export Final Mix**
- Export your session as:
  - `Mashup Test.wav` — Full version
  - `Mashup Test_1.wav` — Highlighted excerpt

---


