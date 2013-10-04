https://github.com/SamLau95/rubiks_solver

Blueprint Coding Challenge

Our team decided that the best way to approach the Rubik's Cube problem was to take existing code and try
to modify it to fit the problem rather than reinventing the wheel. Because of this, most of our time was spent
figuring out what the old code does - rather than spending a short amount of time prototyping a Cube class and
spending more time on the later questions, we wanted to spend more time upfront interfacing the cube so that
the later problems would be easy.

We found an open source Rubik's Cube solver at http://pastebin.com/KwGMujyB and used Nitrous.IO to 
collaborate in real-time as opposed to git, which would involve pushing milestones. We documented the old code
on paper and verbally.

Note that we did not implement the solving algorithm ourselves. However, possible ideas for solving algorithms are:
- Breadth-First Search (brute-force, slow, probably only reason for ~5 moves away)
- A* Search (faster with good heuristic - possible to use # of tiles wrong)

Screenshots at http://imgur.com/w29x7IA,beWWBoy,5SlVuxC#0

Sam:
- Helped read and document the old code
- Discovered representation of face and cube objects so we could interface to it
- Wrote readme, organized tasks
- Helped with initializer code
- Debugged parser, suggested features

Nishant:
- Helped read through existing code
- Wrote text parser based on team's discovery of cube representation
- Debugged interface from parser to internal representation
- Worked to interface text representation with python representation

Sumeet:
- Idea of using existing code
- Helped read and document the old code
- Worked on in-depth analysis of classes/representations
- Implementing turning cube faces
