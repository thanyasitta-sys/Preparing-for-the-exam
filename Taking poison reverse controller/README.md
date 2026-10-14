# กินยาพิษปุมกลับด้าน

public class GameBoard() {
#    +private int reverseButton

#    +public int getReverseBotton() {
#        return reverseBotton;
#    }

#   +public void  setReverseBotton(int revers) {
#        this.reverseBotton = revers;
#    }

    public GameBoard() {
#        +setReverseButton(1)
    }

    public void setWormDirection(char c) {
#        +if (reverseBotton == -1) {
#            if (c == 'W') c = 'S';
#            else if (c == 'A') c = 'D';
#            else if (c == 'S') c = 'W';
#            else if (c == 'D') c = 'A';
#       }
    }

    public void eatItem(int index) {
#        +if(type.equals("poison"))
#                reverseBotton = -reverseBotton;
    }

    public void reset() {
#        +setReverseButton(1)
    }
}