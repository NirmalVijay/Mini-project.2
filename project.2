#include <stdio.h>
#include <string.h>

#define MAX_CANDIDATES 5
#define MAX_VOTERS 100

typedef struct {
    char name[50];
    int voteCount;
} Candidate;

typedef struct {
    char voterID[50];
    int hasVoted;
} Voter;

Candidate candidates[MAX_CANDIDATES];
Voter voters[MAX_VOTERS];
int candidateCount = 0;
int voterCount = 0;

void addCandidate(char *name) {
    if (candidateCount < MAX_CANDIDATES) {
        strcpy(candidates[candidateCount].name, name);
        candidates[candidateCount].voteCount = 0;
        candidateCount++;
    } else {
        printf("Maximum number of candidates reached.\n");
    }
}

void registerVoter(char *voterID) {
    if (voterCount < MAX_VOTERS) {
        strcpy(voters[voterCount].voterID, voterID);
        voters[voterCount].hasVoted = 0;
        voterCount++;
    } else {
        printf("Maximum number of voters reached.\n");
 }
}

int findVoter(char *voterID) {
    for (int i = 0; i < voterCount; i++) {
        if (strcmp(voters[i].voterID, voterID) == 0) {
            return i;
        }
    }
    return -1;
}
void vote(char *voterID, int candidateIndex) {
    int voterIndex = findVoter(voterID);
    if (voterIndex == -1) {
        printf("Voter not registered.\n");
        return;
    }
    if (voters[voterIndex].hasVoted) {
        printf("Voter has already voted.\n");
        return;
    }
    if (candidateIndex < 0 || candidateIndex >= candidateCount) {
        printf("Invalid candidate index.\n");
        return;
    }
    candidates[candidateIndex].voteCount++;
    voters[voterIndex].hasVoted = 1;
    printf("Vote cast successfully.\n");
}

void displayResults() {
    printf("Voting Results:\n");
    for (int i = 0; i < candidateCount; i++) {
        printf("%s: %d votes\n", candidates[i].name, candidates[i].voteCount);
    }
}
int main() {
    addCandidate("Alice");
    addCandidate("Bob");
    addCandidate("Charlie");

    registerVoter("Voter1");
    registerVoter("Voter2");
    registerVoter("Voter3");

    vote("Voter1", 0);
    vote("Voter2", 1);
    vote("Voter3", 1);

    displayResults();

return 0;
}
