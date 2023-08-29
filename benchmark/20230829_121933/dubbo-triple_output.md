# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.089 ops/ms
# Warmup Iteration   2: 5.395 ops/ms
# Warmup Iteration   3: 8.814 ops/ms
Iteration   1: 9.269 ops/ms
Iteration   2: 9.535 ops/ms
Iteration   3: 9.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.350 ±(99.9%) 2.927 ops/ms [Average]
  (min, avg, max) = (9.247, 9.350, 9.535), stdev = 0.160
  CI (99.9%): [6.423, 12.278] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.707 ops/ms
# Warmup Iteration   2: 8.387 ops/ms
# Warmup Iteration   3: 9.221 ops/ms
Iteration   1: 9.300 ops/ms
Iteration   2: 9.429 ops/ms
Iteration   3: 9.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.499 ±(99.9%) 4.414 ops/ms [Average]
  (min, avg, max) = (9.300, 9.499, 9.769), stdev = 0.242
  CI (99.9%): [5.085, 13.913] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.560 ops/ms
# Warmup Iteration   2: 7.867 ops/ms
# Warmup Iteration   3: 9.075 ops/ms
Iteration   1: 9.372 ops/ms
Iteration   2: 9.197 ops/ms
Iteration   3: 9.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.207 ±(99.9%) 2.904 ops/ms [Average]
  (min, avg, max) = (9.054, 9.207, 9.372), stdev = 0.159
  CI (99.9%): [6.304, 12.111] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.151 ops/ms
# Warmup Iteration   2: 7.129 ops/ms
# Warmup Iteration   3: 7.596 ops/ms
Iteration   1: 7.786 ops/ms
Iteration   2: 7.980 ops/ms
Iteration   3: 7.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.910 ±(99.9%) 1.965 ops/ms [Average]
  (min, avg, max) = (7.786, 7.910, 7.980), stdev = 0.108
  CI (99.9%): [5.945, 9.874] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.345 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.003 ms/op
Iteration   1: 3.438 ±(99.9%) 0.006 ms/op
Iteration   2: 3.459 ±(99.9%) 0.005 ms/op
Iteration   3: 3.503 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.466 ±(99.9%) 0.606 ms/op [Average]
  (min, avg, max) = (3.438, 3.466, 3.503), stdev = 0.033
  CI (99.9%): [2.861, 4.072] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.812 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.005 ms/op
Iteration   1: 3.391 ±(99.9%) 0.005 ms/op
Iteration   2: 3.396 ±(99.9%) 0.005 ms/op
Iteration   3: 3.355 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.381 ±(99.9%) 0.407 ms/op [Average]
  (min, avg, max) = (3.355, 3.381, 3.396), stdev = 0.022
  CI (99.9%): [2.973, 3.788] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.845 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.797 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.008 ms/op
Iteration   1: 3.517 ±(99.9%) 0.009 ms/op
Iteration   2: 3.475 ±(99.9%) 0.007 ms/op
Iteration   3: 3.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.488 ±(99.9%) 0.457 ms/op [Average]
  (min, avg, max) = (3.471, 3.488, 3.517), stdev = 0.025
  CI (99.9%): [3.030, 3.945] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.884 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.367 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.195 ±(99.9%) 0.005 ms/op
Iteration   1: 4.079 ±(99.9%) 0.010 ms/op
Iteration   2: 4.090 ±(99.9%) 0.006 ms/op
Iteration   3: 3.993 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.054 ±(99.9%) 0.971 ms/op [Average]
  (min, avg, max) = (3.993, 4.054, 4.090), stdev = 0.053
  CI (99.9%): [3.083, 5.025] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.309 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.973 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.010 ms/op
Iteration   1: 3.450 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.210 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   6.406 ms/op
                 createUser·p0.999:  18.971 ms/op
                 createUser·p0.9999: 21.445 ms/op
                 createUser·p1.00:   22.675 ms/op

Iteration   2: 3.411 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.797 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.250 ms/op
                 createUser·p0.999:  20.361 ms/op
                 createUser·p0.9999: 23.560 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   3: 3.402 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  19.202 ms/op
                 createUser·p0.9999: 25.808 ms/op
                 createUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280551
  mean =      3.421 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16388 
    [ 2.500,  5.000) = 256305 
    [ 5.000,  7.500) = 6415 
    [ 7.500, 10.000) = 793 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.148 ms/op
     p(99.9000) =     19.202 ms/op
     p(99.9900) =     24.769 ms/op
     p(99.9990) =     26.692 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.989 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.643 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.457 ±(99.9%) 0.008 ms/op
Iteration   1: 3.330 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.382 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  9.552 ms/op
                 existUser·p0.9999: 17.774 ms/op
                 existUser·p1.00:   18.547 ms/op

Iteration   2: 3.443 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   6.270 ms/op
                 existUser·p0.999:  16.764 ms/op
                 existUser·p0.9999: 20.175 ms/op
                 existUser·p1.00:   21.365 ms/op

Iteration   3: 3.395 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.266 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   6.242 ms/op
                 existUser·p0.999:  19.121 ms/op
                 existUser·p0.9999: 26.725 ms/op
                 existUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283145
  mean =      3.389 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7644 
    [ 2.500,  5.000) = 268593 
    [ 5.000,  7.500) = 5415 
    [ 7.500, 10.000) = 1011 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     12.990 ms/op
     p(99.9900) =     25.221 ms/op
     p(99.9990) =     28.170 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.599 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.786 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.740 ±(99.9%) 0.012 ms/op
Iteration   1: 3.489 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.767 ms/op
                 getUser·p0.999:  15.401 ms/op
                 getUser·p0.9999: 25.281 ms/op
                 getUser·p1.00:   29.295 ms/op

Iteration   2: 3.427 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  21.759 ms/op
                 getUser·p0.9999: 25.450 ms/op
                 getUser·p1.00:   27.165 ms/op

Iteration   3: 3.406 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.448 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  20.079 ms/op
                 getUser·p0.9999: 27.808 ms/op
                 getUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278706
  mean =      3.440 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7329 
    [ 2.500,  5.000) = 262992 
    [ 5.000,  7.500) = 6680 
    [ 7.500, 10.000) = 1199 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     15.401 ms/op
     p(99.9900) =     27.034 ms/op
     p(99.9990) =     29.243 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.256 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.558 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.208 ±(99.9%) 0.014 ms/op
Iteration   1: 4.154 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.716 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   8.274 ms/op
                 listUser·p0.999:  20.152 ms/op
                 listUser·p0.9999: 23.504 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   2: 4.187 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.763 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   8.170 ms/op
                 listUser·p0.999:  15.968 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   17.924 ms/op

Iteration   3: 4.039 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.921 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   8.020 ms/op
                 listUser·p0.999:  15.803 ms/op
                 listUser·p0.9999: 21.662 ms/op
                 listUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232536
  mean =      4.126 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 220790 
    [ 5.000,  7.500) = 8174 
    [ 7.500, 10.000) = 2698 
    [10.000, 12.500) = 310 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 216 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.716 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     16.417 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     24.041 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.350 ± 2.927  ops/ms
ClientPb.existUser                       thrpt       3   9.499 ± 4.414  ops/ms
ClientPb.getUser                         thrpt       3   9.207 ± 2.904  ops/ms
ClientPb.listUser                        thrpt       3   7.910 ± 1.965  ops/ms
ClientPb.createUser                       avgt       3   3.466 ± 0.606   ms/op
ClientPb.existUser                        avgt       3   3.381 ± 0.407   ms/op
ClientPb.getUser                          avgt       3   3.488 ± 0.457   ms/op
ClientPb.listUser                         avgt       3   4.054 ± 0.971   ms/op
ClientPb.createUser                     sample  280551   3.421 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.797           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.322           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.148           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.202           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.769           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.935           ms/op
ClientPb.existUser                      sample  283145   3.389 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.081           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.194           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.177           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.990           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.221           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.967           ms/op
ClientPb.getUser                        sample  278706   3.440 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.087           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.301           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.472           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.401           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.034           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.295           ms/op
ClientPb.listUser                       sample  232536   4.126 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.716           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.005           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.143           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.417           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.610           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.216           ms/op
