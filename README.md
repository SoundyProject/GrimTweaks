# GrimTweaks

Minimalist AI writing assistant  
Quick text fixes + conversational AI chat

## What this is

Simple web tool that helps with English text editing and generation.  
Two main ways of using it:

- **Quick Fix** – paste text, get instant grammar/punctuation/spelling/style corrections  
- **GrimAI** – regular chat interface where you can ask for writing from scratch, rewriting, tone changes, ideas, summaries, etc.

Everything runs in the browser with a very clean, dark interface. No unnecessary elements.

## Current features

- No registration required (for now)
- Very fast responses
- Strong focus on privacy – texts are not stored after processing
- Free usage up to 1000 characters
- Basic grammar, punctuation and spelling fixes
- Early version of conversational chat (GrimAI)

## Planned / coming features

- Advanced style presets (professional, casual, persuasive, academic, etc.)
- Unlimited characters (premium plan)
- User accounts & login (database-backed)
  - saved texts / history
  - premium subscription status
- Public API for developers
- Support for more languages (starting probably with Polish)

## Current status (late 2025)

|
 Feature                        
|
 Status              
|
 Notes                                      
|
|
--------------------------------
|
---------------------
|
--------------------------------------------
|
|
 Basic grammar & punctuation    
|
 Working             
|
 context aware                              
|
|
 Spelling correction            
|
 Working             
|
|
|
 Simple style improvements      
|
 Basic version       
|
|
|
 Conversational chat (GrimAI)   
|
 Early / beta        
|
 actively developed                         
|
|
 User login & accounts          
|
 Planned             
|
 future addition with database              
|
|
 Saved conversations/texts      
|
 Planned             
|
 requires auth & db                         
|
|
 Premium tier ($9/mo)           
|
 Planned             
|
 unlimited + priority                       
|

## Tech (what's inside)

- Frontend: Next.js (App Router)
- Styling: Tailwind CSS + shadcn/ui
- AI: [Groq / OpenAI / other provider – your choice]
- Deployment: Vercel
- Future: database (probably PostgreSQL / Supabase / Firebase) + authentication

## Privacy (important)

Your text:
- is processed in real time
- is not stored anywhere after the request
- is not used for training any models

This will stay the same even after we add user accounts (only authenticated users will have optional saving feature).

## How to give feedback

The project is very early – literally everything can (and probably will) change.

Best places right now:
- Discord server (link will appear later)
- GitHub issues (when repo becomes public)
- Direct message on X

Any feedback is extremely valuable at this stage.
