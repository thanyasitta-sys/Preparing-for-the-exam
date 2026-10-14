# สิ่งกีดขวางกลางจอ

public class GameBoard {
    public void checkRep() {
        if (gameOver) {
            boolean isOutOfBoard = nextX < 0 || nextX >= boardWidth
                    || nextY < 0 || nextY >= boardHeight 
#                    || (worm.getX() == 13 || worm.getY() == 6); [ทำให้ขึ้น gameOver]
        }
    }
}

public class Worm {
    public void move() {
#        boolean isHitWall = false

#        if (nextX == 13 && nextY == 6) {
#            isHitWall = true;
#        }

#        if (isOutBoard || isOverlapBody || isHitWall) {
            return false;
        }
    }
}

public class GamePanel extends JPanel implements ActionListener, KeyListener {
    public void paintComponent(Graphics g) {
#        g2.setColor(GameConfig.Grey);
#        g2.fillRect(13 * tileSize + 85, 6 * tileSize + 176, tileSize, tileSize);

        wormDrawer.drawWorm(g2, Body, currentDirection, gameBoard.getIsMonthOpen());
    }
}