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
# Warmup Iteration   1: 0.931 ops/ms
# Warmup Iteration   2: 2.187 ops/ms
# Warmup Iteration   3: 4.788 ops/ms
Iteration   1: 5.347 ops/ms
Iteration   2: 5.211 ops/ms
Iteration   3: 5.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.318 ±(99.9%) 1.742 ops/ms [Average]
  (min, avg, max) = (5.211, 5.318, 5.395), stdev = 0.095
  CI (99.9%): [3.576, 7.059] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.381 ops/ms
# Warmup Iteration   2: 4.550 ops/ms
# Warmup Iteration   3: 5.680 ops/ms
Iteration   1: 5.824 ops/ms
Iteration   2: 5.902 ops/ms
Iteration   3: 5.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.898 ±(99.9%) 1.293 ops/ms [Average]
  (min, avg, max) = (5.824, 5.898, 5.966), stdev = 0.071
  CI (99.9%): [4.604, 7.191] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.555 ops/ms
# Warmup Iteration   2: 4.869 ops/ms
# Warmup Iteration   3: 5.409 ops/ms
Iteration   1: 5.676 ops/ms
Iteration   2: 5.632 ops/ms
Iteration   3: 5.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.649 ±(99.9%) 0.430 ops/ms [Average]
  (min, avg, max) = (5.632, 5.649, 5.676), stdev = 0.024
  CI (99.9%): [5.219, 6.079] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.511 ops/ms
# Warmup Iteration   2: 3.714 ops/ms
# Warmup Iteration   3: 4.811 ops/ms
Iteration   1: 4.810 ops/ms
Iteration   2: 4.918 ops/ms
Iteration   3: 4.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.845 ±(99.9%) 1.145 ops/ms [Average]
  (min, avg, max) = (4.808, 4.845, 4.918), stdev = 0.063
  CI (99.9%): [3.700, 5.991] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 21.282 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 7.747 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.058 ±(99.9%) 0.013 ms/op
Iteration   1: 5.989 ±(99.9%) 0.007 ms/op
Iteration   2: 5.675 ±(99.9%) 0.008 ms/op
Iteration   3: 5.658 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.774 ±(99.9%) 3.395 ms/op [Average]
  (min, avg, max) = (5.658, 5.774, 5.989), stdev = 0.186
  CI (99.9%): [2.379, 9.168] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 17.148 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 6.988 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.570 ±(99.9%) 0.010 ms/op
Iteration   1: 5.407 ±(99.9%) 0.011 ms/op
Iteration   2: 5.274 ±(99.9%) 0.008 ms/op
Iteration   3: 5.232 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.304 ±(99.9%) 1.665 ms/op [Average]
  (min, avg, max) = (5.232, 5.304, 5.407), stdev = 0.091
  CI (99.9%): [3.639, 6.970] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.922 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 6.433 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.649 ±(99.9%) 0.006 ms/op
Iteration   1: 5.500 ±(99.9%) 0.009 ms/op
Iteration   2: 5.556 ±(99.9%) 0.007 ms/op
Iteration   3: 5.477 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.511 ±(99.9%) 0.743 ms/op [Average]
  (min, avg, max) = (5.477, 5.511, 5.556), stdev = 0.041
  CI (99.9%): [4.767, 6.254] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 17.860 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 7.999 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.587 ±(99.9%) 0.012 ms/op
Iteration   1: 6.639 ±(99.9%) 0.012 ms/op
Iteration   2: 6.500 ±(99.9%) 0.011 ms/op
Iteration   3: 6.555 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.565 ±(99.9%) 1.272 ms/op [Average]
  (min, avg, max) = (6.500, 6.565, 6.639), stdev = 0.070
  CI (99.9%): [5.293, 7.837] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.206 ±(99.9%) 0.305 ms/op
# Warmup Iteration   2: 7.303 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.073 ±(99.9%) 0.029 ms/op
Iteration   1: 5.630 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.363 ms/op
                 createUser·p0.50:   5.333 ms/op
                 createUser·p0.90:   6.971 ms/op
                 createUser·p0.95:   8.585 ms/op
                 createUser·p0.99:   11.721 ms/op
                 createUser·p0.999:  16.763 ms/op
                 createUser·p0.9999: 29.563 ms/op
                 createUser·p1.00:   30.147 ms/op

Iteration   2: 5.595 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.290 ms/op
                 createUser·p0.50:   5.292 ms/op
                 createUser·p0.90:   6.791 ms/op
                 createUser·p0.95:   7.930 ms/op
                 createUser·p0.99:   10.945 ms/op
                 createUser·p0.999:  26.477 ms/op
                 createUser·p0.9999: 32.200 ms/op
                 createUser·p1.00:   32.834 ms/op

Iteration   3: 5.616 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.638 ms/op
                 createUser·p0.50:   5.300 ms/op
                 createUser·p0.90:   6.717 ms/op
                 createUser·p0.95:   8.266 ms/op
                 createUser·p0.99:   12.000 ms/op
                 createUser·p0.999:  30.150 ms/op
                 createUser·p0.9999: 38.732 ms/op
                 createUser·p1.00:   39.584 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 170997
  mean =      5.613 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 52155 
    [ 5.000,  7.500) = 107157 
    [ 7.500, 10.000) = 7903 
    [10.000, 12.500) = 2589 
    [12.500, 15.000) = 659 
    [15.000, 17.500) = 288 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.290 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      6.832 ms/op
     p(95.0000) =      8.241 ms/op
     p(99.0000) =     11.616 ms/op
     p(99.9000) =     21.922 ms/op
     p(99.9900) =     36.720 ms/op
     p(99.9990) =     39.212 ms/op
     p(99.9999) =     39.584 ms/op
    p(100.0000) =     39.584 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.138 ±(99.9%) 0.274 ms/op
# Warmup Iteration   2: 6.880 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.462 ±(99.9%) 0.021 ms/op
Iteration   1: 5.442 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.273 ms/op
                 existUser·p0.50:   5.087 ms/op
                 existUser·p0.90:   6.922 ms/op
                 existUser·p0.95:   8.282 ms/op
                 existUser·p0.99:   11.190 ms/op
                 existUser·p0.999:  15.675 ms/op
                 existUser·p0.9999: 27.009 ms/op
                 existUser·p1.00:   28.246 ms/op

Iteration   2: 5.382 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.253 ms/op
                 existUser·p0.50:   5.177 ms/op
                 existUser·p0.90:   6.529 ms/op
                 existUser·p0.95:   7.447 ms/op
                 existUser·p0.99:   10.256 ms/op
                 existUser·p0.999:  30.303 ms/op
                 existUser·p0.9999: 35.000 ms/op
                 existUser·p1.00:   37.290 ms/op

Iteration   3: 5.384 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.507 ms/op
                 existUser·p0.50:   5.054 ms/op
                 existUser·p0.90:   6.619 ms/op
                 existUser·p0.95:   8.225 ms/op
                 existUser·p0.99:   12.009 ms/op
                 existUser·p0.999:  28.846 ms/op
                 existUser·p0.9999: 32.018 ms/op
                 existUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177664
  mean =      5.403 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 76483 
    [ 5.000,  7.500) = 89872 
    [ 7.500, 10.000) = 7940 
    [10.000, 12.500) = 2443 
    [12.500, 15.000) = 672 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.253 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      6.685 ms/op
     p(95.0000) =      8.004 ms/op
     p(99.0000) =     11.321 ms/op
     p(99.9000) =     16.877 ms/op
     p(99.9900) =     33.570 ms/op
     p(99.9990) =     37.239 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 20.550 ±(99.9%) 0.377 ms/op
# Warmup Iteration   2: 7.094 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.953 ±(99.9%) 0.025 ms/op
Iteration   1: 5.818 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.458 ms/op
                 getUser·p0.50:   5.415 ms/op
                 getUser·p0.90:   7.545 ms/op
                 getUser·p0.95:   8.913 ms/op
                 getUser·p0.99:   12.517 ms/op
                 getUser·p0.999:  22.088 ms/op
                 getUser·p0.9999: 29.988 ms/op
                 getUser·p1.00:   33.620 ms/op

Iteration   2: 5.779 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   5.300 ms/op
                 getUser·p0.90:   7.881 ms/op
                 getUser·p0.95:   9.208 ms/op
                 getUser·p0.99:   12.763 ms/op
                 getUser·p0.999:  29.336 ms/op
                 getUser·p0.9999: 45.382 ms/op
                 getUser·p1.00:   46.203 ms/op

Iteration   3: 5.746 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.748 ms/op
                 getUser·p0.50:   5.341 ms/op
                 getUser·p0.90:   7.291 ms/op
                 getUser·p0.95:   8.454 ms/op
                 getUser·p0.99:   11.977 ms/op
                 getUser·p0.999:  28.782 ms/op
                 getUser·p0.9999: 34.556 ms/op
                 getUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 165924
  mean =      5.781 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 47678 
    [ 5.000, 10.000) = 113522 
    [10.000, 15.000) = 4194 
    [15.000, 20.000) = 279 
    [20.000, 25.000) = 83 
    [25.000, 30.000) = 65 
    [30.000, 35.000) = 71 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      7.545 ms/op
     p(95.0000) =      8.864 ms/op
     p(99.0000) =     12.419 ms/op
     p(99.9000) =     25.526 ms/op
     p(99.9900) =     43.242 ms/op
     p(99.9990) =     45.728 ms/op
     p(99.9999) =     46.203 ms/op
    p(100.0000) =     46.203 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.683 ±(99.9%) 0.321 ms/op
# Warmup Iteration   2: 7.731 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.786 ±(99.9%) 0.030 ms/op
Iteration   1: 6.621 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   6.201 ms/op
                 listUser·p0.90:   8.118 ms/op
                 listUser·p0.95:   9.994 ms/op
                 listUser·p0.99:   13.870 ms/op
                 listUser·p0.999:  28.354 ms/op
                 listUser·p0.9999: 30.965 ms/op
                 listUser·p1.00:   31.654 ms/op

Iteration   2: 6.630 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.552 ms/op
                 listUser·p0.50:   6.152 ms/op
                 listUser·p0.90:   8.348 ms/op
                 listUser·p0.95:   10.011 ms/op
                 listUser·p0.99:   13.369 ms/op
                 listUser·p0.999:  30.409 ms/op
                 listUser·p0.9999: 34.364 ms/op
                 listUser·p1.00:   36.045 ms/op

Iteration   3: 6.652 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.904 ms/op
                 listUser·p0.50:   6.259 ms/op
                 listUser·p0.90:   8.159 ms/op
                 listUser·p0.95:   9.683 ms/op
                 listUser·p0.99:   12.796 ms/op
                 listUser·p0.999:  26.342 ms/op
                 listUser·p0.9999: 32.348 ms/op
                 listUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 144705
  mean =      6.634 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 5024 
    [ 5.000,  7.500) = 118878 
    [ 7.500, 10.000) = 13845 
    [10.000, 12.500) = 4859 
    [12.500, 15.000) = 1322 
    [15.000, 17.500) = 392 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 95 
    [30.000, 32.500) = 71 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      6.201 ms/op
     p(90.0000) =      8.200 ms/op
     p(95.0000) =      9.880 ms/op
     p(99.0000) =     13.255 ms/op
     p(99.9000) =     29.000 ms/op
     p(99.9900) =     33.410 ms/op
     p(99.9990) =     35.986 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.318 ± 1.742  ops/ms
ClientPb.existUser                       thrpt       3   5.898 ± 1.293  ops/ms
ClientPb.getUser                         thrpt       3   5.649 ± 0.430  ops/ms
ClientPb.listUser                        thrpt       3   4.845 ± 1.145  ops/ms
ClientPb.createUser                       avgt       3   5.774 ± 3.395   ms/op
ClientPb.existUser                        avgt       3   5.304 ± 1.665   ms/op
ClientPb.getUser                          avgt       3   5.511 ± 0.743   ms/op
ClientPb.listUser                         avgt       3   6.565 ± 1.272   ms/op
ClientPb.createUser                     sample  170997   5.613 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.290           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.308           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.832           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.241           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.616           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.922           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.720           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.584           ms/op
ClientPb.existUser                      sample  177664   5.403 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.253           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.104           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.685           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.004           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.321           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.877           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.570           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.290           ms/op
ClientPb.getUser                        sample  165924   5.781 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.850           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.349           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.545           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.864           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.419           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.526           ms/op
ClientPb.getUser:getUser·p0.9999        sample          43.242           ms/op
ClientPb.getUser:getUser·p1.00          sample          46.203           ms/op
ClientPb.listUser                       sample  144705   6.634 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.552           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.201           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.200           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.880           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.255           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.000           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.410           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.045           ms/op
