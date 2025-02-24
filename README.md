This bug report describes an issue where the Firebase getDoc() method incorrectly returns 'No such document!' even when the target document exists in the Firestore database.  The provided JavaScript code demonstrates the problem and a potential solution.  The issue appears to stem from a possible mismatch between the specified document path and the actual document path in Firestore or from incorrect security rules.