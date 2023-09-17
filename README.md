# Chess-game
Here we have project screenshot :

![screenshot](https://github.com/AndyMagwayer/Chess-game/blob/main/4-9-23.png)

### Chess Game (VS Computer)

I am gonna showing to you how to code a chess game with javascript. in this javascript chess game you can play with computer, flip board and set position. in this code you will learn to use chessboardjs and chess.js library❗️

## Deploy:
https://chess-game-magamed.netlify.app/

# FEN Notation

![screenshot](https://github.com/AndyMagwayer/Chess-game/blob/main/Screenshot%202023-09-01%20200909.png)

FEN (Forsyth-Edwards Notation) is a standard notation used to represent a particular chessboard position. It provides a concise and human-readable way to describe the placement of chess pieces on the board, as well as other important information about the position. Here's how FEN notation works such as:

A FEN string consists of six fields separated by spaces:

1. **Piece Placement (8 ranks)**: This field represents the positions of the pieces on the board. Each rank is represented by a series of characters, where:
   - `K` represents a white king.
   - `Q` represents a white queen.
   - `R` represents a white rook.
   - `B` represents a white bishop.
   - `N` represents a white knight.
   - `P` represents a white pawn.
   - `k` represents a black king.
   - `q` represents a black queen.
   - `r` represents a black rook.
   - `b` represents a black bishop.
   - `n` represents a black knight.
   - `p` represents a black pawn.
   - Digits (1-8) represent empty squares, with the number indicating the count of consecutive empty squares.

   For example, `rnbqkbnr/pppppppp/8/8/8/8/PPPPPPPP/RNBQKBNR` represents the starting position of a chess game.

2. **Active Color (1 character)**: This field indicates which player's turn it is to move. `w` represents White's turn, and `b` represents Black's turn.

3. **Castling Availability (1-4 characters)**: This field indicates whether castling is still available for each player. The characters used are:
   - `K` for White kingside castling.
   - `Q` for White queenside castling.
   - `k` for Black kingside castling.
   - `q` for Black queenside castling.
   - `-` if no castling is possible.

4. **En Passant Target Square (1-2 characters)**: If a pawn has just moved two squares forward from its starting position, this field represents the square where the opposing pawn can capture en passant. Otherwise, it is represented as `-`.

5. **Halfmove Clock (1-2 characters)**: This field represents the number of half-moves (ply) since the last pawn move or capture. It is used for the fifty-move rule.

6. **Fullmove Number (1-2 characters)**: This field represents the number of full moves (complete turns) in the game. It starts at 1 and is incremented after Black's move.

Here's an example FEN string:
```
rnbqkb1r/ppp1pppp/5n2/3p4/3P4/8/PPP2PPP/RNBQKBNR w KQkq - 0 4
```
This FEN represents a specific board position where it's White's turn to move, both sides have the potential to castle kingside and queenside, there's no en passant target square, the halfmove clock is 0, and the fullmove number is 4.

You can use FEN notation to record and share specific chess positions and use them for various purposes, including setting up custom positions for analysis or practice.

<br>
<br>
## Portfolio: https://portfolio-magamed.netlify.app/

![Image alt](https://github.com/AndyMagwayer/Portfolio-Website/blob/main/Screenshot%202023-09-17%20094045.png)
# My Portfolio Website

This is a personal portfolio website that showcases my work, skills, and experiences as a software developer. The website is designed to provide a visually appealing and user-friendly interface for visitors to navigate through my projects and learn more about me.

## Features

- **Home Page**: The home page provides a brief introduction about myself and highlights my key skills and expertise. It also includes a call-to-action section to encourage visitors to explore further.

- **Projects**: This section showcases a selection of my best projects. Each project is displayed with a thumbnail image, a short description, and a link to view more details. Visitors can easily browse through the projects and get a glimpse of my technical abilities.

- **Skills**: This page provides a detailed list of my technical skills and proficiencies. It includes programming languages, frameworks, tools, and methodologies that I am proficient in. This section helps potential employers or clients understand my technical expertise.

- **Experience**: This section outlines my professional experience, including previous job positions, internships, or freelance work. It includes details such as company names, job titles, and a brief description of my responsibilities and achievements in each role.

- **Contact**: The contact page provides visitors with a convenient way to get in touch with me. It includes a contact form where users can submit their inquiries or messages directly to my email address. Additionally, my social media profiles and professional networks are also provided for alternative contact methods.

## Technologies Used

- HTML5: Used for structuring the web pages and content.
- CSS3: Used for styling and layout of the website.
- JavaScript: Used for interactive features and dynamic content.
- Bootstrap: Utilized the Bootstrap framework for responsive design and pre-built components.
- GitHub Pages: Hosted the website on GitHub Pages for easy deployment and accessibility.

## Deployment

The website is deployed using GitHub Pages, which allows for easy hosting and sharing of static web pages directly from a GitHub repository. The repository contains all the necessary files and assets for the website, including HTML, CSS, JavaScript, and media files. Any updates or changes made to the repository will be automatically reflected on the live website.

## Conclusion

This portfolio website serves as a showcase of my skills, projects, and experiences in the field of software development. It is designed to provide an engaging and informative experience for visitors, allowing them to learn more about me and my work. The website is easily accessible through GitHub Pages and can be further customized and expanded as my portfolio grows.
