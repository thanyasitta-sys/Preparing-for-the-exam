# ทะแยงเดิน
public class GameBoard {
    public void setWormDirection(char c) {
#         else if ( c == 'Q') {
#            turn(-1, -1);
#        } else if ( c == 'E') {
#            turn(1, -1);
#        } else if ( c == 'C') {
#            turn(1, 1);
#        } else if ( c == 'Z') {
#            turn(-1, 1);
#        }
    }
}

public class GamePanel extends JPanel implements ActionListener, KeyListener {
        public void keyPressed(KeyEvent e) {
#       VK_UP -> VK_W
#        if (e.getKeyCode() == KeyEvent.VK_W && isKeyPress == false) {
            gameBoard.setWormDirection('W');
            currentDirection = 'W';
#       VK_DOWN -> VK_S
        } else if (
#            e.getKeyCode() == KeyEvent.VK_S && isKeyPress == false
        ) {
            gameBoard.setWormDirection('S');
            currentDirection = 'S';
#       VK_LEFT -> VK_A
        } else if (
#            e.getKeyCode() == KeyEvent.VK_A && isKeyPress == false
        ) {
            gameBoard.setWormDirection('A');
            currentDirection = 'A';
#       VK_RIGHT -> VK_D
        } else if (
#            e.getKeyCode() == KeyEvent.VK_D && isKeyPress == false
        ) {
            gameBoard.setWormDirection('D');
            currentDirection = 'D';
#        } else if (e.getKeyCode() == KeyEvent.VK_Q && isKeyPress == false) {
#            gameBoard.setWormDirection('Q');
#            currentDirection = 'Q';
#        } else if (e.getKeyCode() == KeyEvent.VK_E && isKeyPress == false) {
#            gameBoard.setWormDirection('E');
#            currentDirection = 'E';
#        } else if (e.getKeyCode() == KeyEvent.VK_Z && isKeyPress == false) {
#            gameBoard.setWormDirection('Z');
#            currentDirection = 'Z';
#        } else if (e.getKeyCode() == KeyEvent.VK_C && isKeyPress == false) {
#            gameBoard.setWormDirection('C');
#            currentDirection = 'C';
#        } 
        isKeyPress = true;
    }
}