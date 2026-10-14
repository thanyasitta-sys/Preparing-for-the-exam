# กินแอปเปิ้ลปล้วยาว 2 ข้อ

public class GameBoard {
    public void eatItem(int index) {
        if (collision(worm.getX(), worm.getY(), items.get(index).getX(), items.get(index).getY())) {
#            if (type.equals("goldApple")) {
#                worm.addTail();
#                worm.addTail();
#            }
        }
    }
}