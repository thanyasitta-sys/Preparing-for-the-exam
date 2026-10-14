# แก้ดรอปเรต

public class GameBoard {
    public void addItem(float initialSpawnTime) {
#        int randomItemType = random.nextInt(100);
#        if (randomItemType < 50)
            items.add(new Apple(x, y, initialSpawnTime));

#        else if (randomItemType < 60)
            items.add(new GoldApple(x, y, initialSpawnTime));

#        else if (randomItemType < 80)
            items.add(new SpeedPotion(x, y, initialSpawnTime));
            
#        else
            items.add(new Poison(x, y, initialSpawnTime));
    }
}