# Robotic Project

## Takım Arkadaşları

- 032190032 Mine Korkmaz
- 032190060 Fatma Büşra Tilki
- 032190080 Fatma Nur Ayyıldız

## Proje Hakkında

Bu proje, Robot Tasarımı ve Uygulamaları dersi kapsamında gerçekleştirilmiştir. Çalışmamızda PPO (Proximal Policy Optimization), DDPG (Deep Deterministic Policy Gradient) ve SAC (Soft Actor-Critic) algoritmalarını kullanarak, Humanoid ve Mountain Car Continuous ortamlarında bu algoritmaların performanslarını karşılaştırmayı hedefledik.

### Kullanılan Algoritmalar
- [**PPO (Proximal Policy Optimization):**](https://spinningup.openai.com/en/latest/algorithms/ppo.html) Politikaya dayalı bir derin pekiştirmeli öğrenme algoritmasıdır ve denge ile veri verimliliği sağlamayı amaçlar.
- [**DDPG (Deep Deterministic Policy Gradient):**](https://spinningup.openai.com/en/latest/algorithms/ddpg.html) Sürekli eylem alanlarında çalışan, aktör-eleştirmen (actor-critic) mimarisine sahip bir algoritmadır.
- [**SAC (Soft Actor-Critic):**](https://spinningup.openai.com/en/latest/algorithms/sac.html) Entropi düzenlemeli bir RL algoritması olup, keşif ve sömürü dengesini optimize etmeye odaklanır.

Daha fazla detay için ilgili algoritmaların web sitelerini inceleyebilirsiniz.

### Kullanılan Ortamlar (Environments)
- [**Humanoid (MuJoCo):**](https://gymnasium.farama.org/environments/mujoco/humanoid/) İnsan benzeri bir robotun yürüyüşünü optimize etmeye dayalı karmaşık bir ortamdır.
- [**Mountain Car Continuous (OpenAI Gym):**](https://gymnasium.farama.org/environments/classic_control/mountain_car_continuous/) Arabanın tepeyi aşmasını sağlamaya dayalı sürekli bir kontrol problemidir.

Daha detaylı bilgi için yukarıdaki bağlantıları inceleyebilirsiniz.