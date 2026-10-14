# กินยาพิษแล้วตัวสั้น


public classs Worm {
#    +public void removeTail() {
#        if (bodys.isEmpty()) throw new IllegalStateException();
#        bodys.remove(bodys.size()-1);
#   }
}

public class GameBoard() {
    public void eatItem(int index) {
        if (collision(worm.getX(), worm.getY(), items.get(index).getX(), items.get(index).getY())) {
#            +if(type.equals("poison")){
#                worm.removeTail();
#               if (worm.getBodySize() <= 0)
#                    setGameOver(true);
#           }
        }
    }
}