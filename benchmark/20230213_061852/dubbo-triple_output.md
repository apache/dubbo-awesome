# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.985 ops/ms
# Warmup Iteration   2: 5.399 ops/ms
# Warmup Iteration   3: 8.974 ops/ms
Iteration   1: 9.385 ops/ms
Iteration   2: 9.035 ops/ms
Iteration   3: 9.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.379 ±(99.9%) 6.227 ops/ms [Average]
  (min, avg, max) = (9.035, 9.379, 9.717), stdev = 0.341
  CI (99.9%): [3.152, 15.605] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.953 ops/ms
# Warmup Iteration   2: 8.448 ops/ms
# Warmup Iteration   3: 9.433 ops/ms
Iteration   1: 9.508 ops/ms
Iteration   2: 10.184 ops/ms
Iteration   3: 9.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.755 ±(99.9%) 6.812 ops/ms [Average]
  (min, avg, max) = (9.508, 9.755, 10.184), stdev = 0.373
  CI (99.9%): [2.942, 16.567] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.110 ops/ms
# Warmup Iteration   2: 8.653 ops/ms
# Warmup Iteration   3: 8.852 ops/ms
Iteration   1: 9.518 ops/ms
Iteration   2: 9.487 ops/ms
Iteration   3: 9.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.405 ±(99.9%) 3.107 ops/ms [Average]
  (min, avg, max) = (9.209, 9.405, 9.518), stdev = 0.170
  CI (99.9%): [6.298, 12.512] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.783 ops/ms
# Warmup Iteration   2: 6.916 ops/ms
# Warmup Iteration   3: 7.673 ops/ms
Iteration   1: 8.172 ops/ms
Iteration   2: 8.107 ops/ms
Iteration   3: 8.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.126 ±(99.9%) 0.737 ops/ms [Average]
  (min, avg, max) = (8.098, 8.126, 8.172), stdev = 0.040
  CI (99.9%): [7.389, 8.863] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.992 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.586 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.571 ±(99.9%) 0.008 ms/op
Iteration   1: 3.413 ±(99.9%) 0.009 ms/op
Iteration   2: 3.377 ±(99.9%) 0.007 ms/op
Iteration   3: 3.377 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.389 ±(99.9%) 0.376 ms/op [Average]
  (min, avg, max) = (3.377, 3.389, 3.413), stdev = 0.021
  CI (99.9%): [3.013, 3.766] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.869 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.004 ms/op
Iteration   1: 3.296 ±(99.9%) 0.011 ms/op
Iteration   2: 3.300 ±(99.9%) 0.012 ms/op
Iteration   3: 3.276 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.291 ±(99.9%) 0.229 ms/op [Average]
  (min, avg, max) = (3.276, 3.291, 3.300), stdev = 0.013
  CI (99.9%): [3.062, 3.520] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.371 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.685 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.427 ±(99.9%) 0.005 ms/op
Iteration   1: 3.532 ±(99.9%) 0.009 ms/op
Iteration   2: 3.341 ±(99.9%) 0.011 ms/op
Iteration   3: 3.421 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.431 ±(99.9%) 1.755 ms/op [Average]
  (min, avg, max) = (3.341, 3.431, 3.532), stdev = 0.096
  CI (99.9%): [1.677, 5.186] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.689 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.453 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.141 ±(99.9%) 0.009 ms/op
Iteration   1: 4.034 ±(99.9%) 0.008 ms/op
Iteration   2: 3.902 ±(99.9%) 0.012 ms/op
Iteration   3: 3.921 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.952 ±(99.9%) 1.302 ms/op [Average]
  (min, avg, max) = (3.902, 3.952, 4.034), stdev = 0.071
  CI (99.9%): [2.650, 5.254] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.771 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.017 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.011 ms/op
Iteration   1: 3.373 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  19.858 ms/op
                 createUser·p0.9999: 23.219 ms/op
                 createUser·p1.00:   23.822 ms/op

Iteration   2: 3.374 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  20.749 ms/op
                 createUser·p0.9999: 25.428 ms/op
                 createUser·p1.00:   26.804 ms/op

Iteration   3: 3.301 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.851 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.131 ms/op
                 createUser·p0.999:  17.894 ms/op
                 createUser·p0.9999: 30.048 ms/op
                 createUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 286414
  mean =      3.349 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6893 
    [ 2.500,  5.000) = 274502 
    [ 5.000,  7.500) = 4116 
    [ 7.500, 10.000) = 496 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     19.825 ms/op
     p(99.9900) =     27.930 ms/op
     p(99.9990) =     30.081 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.001 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.676 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.009 ms/op
Iteration   1: 3.280 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.489 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  13.902 ms/op
                 existUser·p0.9999: 22.651 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   2: 3.282 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.667 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  10.118 ms/op
                 existUser·p0.9999: 26.968 ms/op
                 existUser·p1.00:   27.689 ms/op

Iteration   3: 3.294 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.319 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  11.611 ms/op
                 existUser·p0.9999: 28.120 ms/op
                 existUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292084
  mean =      3.285 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4035 
    [ 2.500,  5.000) = 283268 
    [ 5.000,  7.500) = 3897 
    [ 7.500, 10.000) = 503 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     12.099 ms/op
     p(99.9900) =     27.623 ms/op
     p(99.9990) =     28.844 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.560 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.796 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.557 ±(99.9%) 0.010 ms/op
Iteration   1: 3.320 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.683 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   5.038 ms/op
                 getUser·p0.999:  11.338 ms/op
                 getUser·p0.9999: 22.786 ms/op
                 getUser·p1.00:   24.347 ms/op

Iteration   2: 3.643 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   5.169 ms/op
                 getUser·p0.99:   6.318 ms/op
                 getUser·p0.999:  21.052 ms/op
                 getUser·p0.9999: 24.510 ms/op
                 getUser·p1.00:   29.917 ms/op

Iteration   3: 3.403 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.481 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   6.614 ms/op
                 getUser·p0.999:  20.580 ms/op
                 getUser·p0.9999: 25.304 ms/op
                 getUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278050
  mean =      3.450 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5282 
    [ 2.500,  5.000) = 263803 
    [ 5.000,  7.500) = 7946 
    [ 7.500, 10.000) = 669 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     11.418 ms/op
     p(99.9900) =     24.608 ms/op
     p(99.9990) =     26.191 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.855 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.419 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.013 ms/op
Iteration   1: 4.046 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.958 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   7.677 ms/op
                 listUser·p0.999:  19.986 ms/op
                 listUser·p0.9999: 22.810 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   2: 4.011 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.568 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  16.339 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   3: 3.894 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  15.167 ms/op
                 listUser·p0.9999: 16.679 ms/op
                 listUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241087
  mean =      3.982 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 232334 
    [ 5.000,  7.500) = 6492 
    [ 7.500, 10.000) = 1462 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 209 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.958 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     15.712 ms/op
     p(99.9900) =     21.853 ms/op
     p(99.9990) =     23.819 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.379 ± 6.227  ops/ms
ClientPb.existUser                       thrpt       3   9.755 ± 6.812  ops/ms
ClientPb.getUser                         thrpt       3   9.405 ± 3.107  ops/ms
ClientPb.listUser                        thrpt       3   8.126 ± 0.737  ops/ms
ClientPb.createUser                       avgt       3   3.389 ± 0.376   ms/op
ClientPb.existUser                        avgt       3   3.291 ± 0.229   ms/op
ClientPb.getUser                          avgt       3   3.431 ± 1.755   ms/op
ClientPb.listUser                         avgt       3   3.952 ± 1.302   ms/op
ClientPb.createUser                     sample  286414   3.349 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.961           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.236           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.612           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.825           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.930           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.081           ms/op
ClientPb.existUser                      sample  292084   3.285 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.319           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.867           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.562           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.099           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.623           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.688           ms/op
ClientPb.getUser                        sample  278050   3.450 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.204           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.301           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.334           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.119           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.418           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.608           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.917           ms/op
ClientPb.listUser                       sample  241087   3.982 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.958           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.389           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.712           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.853           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.625           ms/op
