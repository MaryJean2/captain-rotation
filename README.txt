CAPTAINS ROTATION PLANNER v1

People:
- D = David
- E = Ewan
- H = handover

Imported schedule:
- Existing Captain workbook data from Nov 2021 through Oct 2027 is preloaded.

Contract calculation:
- Contract year: 01-Nov through 31-Oct
- Contracted days: 185 each
- H days count as onboard in the contract total for both captains, matching the current spreadsheet structure.

Firebase:
- Uses the same Firebase project as the other rotation planners.
- Firestore path: captainsRotation/shared
- Create David and Ewan users in Firebase Authentication.
- Publish the rules in FIREBASE-RULES.txt so this third planner can sync.

GitHub:
- Recommended repository: captains-rotation
- Upload the CONTENTS of this folder to the repository root.
- Enable GitHub Pages from main / (root).
