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
# Warmup Iteration   1: 1.177 ops/ms
# Warmup Iteration   2: 2.676 ops/ms
# Warmup Iteration   3: 5.832 ops/ms
Iteration   1: 5.913 ops/ms
Iteration   2: 6.320 ops/ms
Iteration   3: 6.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.219 ±(99.9%) 4.936 ops/ms [Average]
  (min, avg, max) = (5.913, 6.219, 6.425), stdev = 0.271
  CI (99.9%): [1.283, 11.155] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.749 ops/ms
# Warmup Iteration   2: 5.396 ops/ms
# Warmup Iteration   3: 6.780 ops/ms
Iteration   1: 6.850 ops/ms
Iteration   2: 6.835 ops/ms
Iteration   3: 6.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.745 ±(99.9%) 3.105 ops/ms [Average]
  (min, avg, max) = (6.548, 6.745, 6.850), stdev = 0.170
  CI (99.9%): [3.640, 9.850] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.631 ops/ms
# Warmup Iteration   2: 5.039 ops/ms
# Warmup Iteration   3: 6.245 ops/ms
Iteration   1: 6.733 ops/ms
Iteration   2: 6.395 ops/ms
Iteration   3: 6.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.444 ±(99.9%) 4.890 ops/ms [Average]
  (min, avg, max) = (6.204, 6.444, 6.733), stdev = 0.268
  CI (99.9%): [1.554, 11.335] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.845 ops/ms
# Warmup Iteration   2: 4.676 ops/ms
# Warmup Iteration   3: 5.573 ops/ms
Iteration   1: 5.429 ops/ms
Iteration   2: 5.777 ops/ms
Iteration   3: 5.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.605 ±(99.9%) 3.180 ops/ms [Average]
  (min, avg, max) = (5.429, 5.605, 5.777), stdev = 0.174
  CI (99.9%): [2.426, 8.785] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 17.303 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 5.672 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.221 ±(99.9%) 0.012 ms/op
Iteration   1: 4.907 ±(99.9%) 0.016 ms/op
Iteration   2: 4.907 ±(99.9%) 0.013 ms/op
Iteration   3: 4.893 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.902 ±(99.9%) 0.144 ms/op [Average]
  (min, avg, max) = (4.893, 4.902, 4.907), stdev = 0.008
  CI (99.9%): [4.758, 5.047] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.186 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 5.307 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.792 ±(99.9%) 0.009 ms/op
Iteration   1: 4.796 ±(99.9%) 0.009 ms/op
Iteration   2: 4.800 ±(99.9%) 0.012 ms/op
Iteration   3: 4.711 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.769 ±(99.9%) 0.917 ms/op [Average]
  (min, avg, max) = (4.711, 4.769, 4.800), stdev = 0.050
  CI (99.9%): [3.852, 5.686] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 17.375 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.885 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.303 ±(99.9%) 0.009 ms/op
Iteration   1: 5.035 ±(99.9%) 0.013 ms/op
Iteration   2: 5.101 ±(99.9%) 0.009 ms/op
Iteration   3: 4.951 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.029 ±(99.9%) 1.377 ms/op [Average]
  (min, avg, max) = (4.951, 5.029, 5.101), stdev = 0.075
  CI (99.9%): [3.652, 6.406] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.129 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 6.895 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.879 ±(99.9%) 0.009 ms/op
Iteration   1: 5.788 ±(99.9%) 0.011 ms/op
Iteration   2: 5.822 ±(99.9%) 0.010 ms/op
Iteration   3: 5.910 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.840 ±(99.9%) 1.147 ms/op [Average]
  (min, avg, max) = (5.788, 5.840, 5.910), stdev = 0.063
  CI (99.9%): [4.693, 6.987] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.217 ±(99.9%) 0.307 ms/op
# Warmup Iteration   2: 6.334 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.525 ±(99.9%) 0.023 ms/op
Iteration   1: 4.937 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.411 ms/op
                 createUser·p0.50:   4.702 ms/op
                 createUser·p0.90:   5.939 ms/op
                 createUser·p0.95:   6.840 ms/op
                 createUser·p0.99:   9.273 ms/op
                 createUser·p0.999:  21.756 ms/op
                 createUser·p0.9999: 25.690 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   2: 4.875 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.408 ms/op
                 createUser·p0.50:   4.653 ms/op
                 createUser·p0.90:   5.751 ms/op
                 createUser·p0.95:   6.291 ms/op
                 createUser·p0.99:   9.552 ms/op
                 createUser·p0.999:  16.019 ms/op
                 createUser·p0.9999: 27.099 ms/op
                 createUser·p1.00:   27.886 ms/op

Iteration   3: 5.057 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.408 ms/op
                 createUser·p0.50:   4.776 ms/op
                 createUser·p0.90:   6.078 ms/op
                 createUser·p0.95:   7.291 ms/op
                 createUser·p0.99:   10.065 ms/op
                 createUser·p0.999:  25.202 ms/op
                 createUser·p0.9999: 27.154 ms/op
                 createUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 193516
  mean =      4.955 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 134365 
    [ 5.000,  7.500) = 52697 
    [ 7.500, 10.000) = 4816 
    [10.000, 12.500) = 1120 
    [12.500, 15.000) = 266 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 128 

  Percentiles, ms/op:
      p(0.0000) =      1.411 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      5.915 ms/op
     p(95.0000) =      6.775 ms/op
     p(99.0000) =      9.617 ms/op
     p(99.9000) =     21.544 ms/op
     p(99.9900) =     27.066 ms/op
     p(99.9990) =     28.075 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 14.857 ±(99.9%) 0.218 ms/op
# Warmup Iteration   2: 5.420 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.015 ±(99.9%) 0.018 ms/op
Iteration   1: 4.825 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.212 ms/op
                 existUser·p0.50:   4.596 ms/op
                 existUser·p0.90:   5.874 ms/op
                 existUser·p0.95:   6.463 ms/op
                 existUser·p0.99:   8.585 ms/op
                 existUser·p0.999:  14.008 ms/op
                 existUser·p0.9999: 23.785 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   2: 4.774 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.011 ms/op
                 existUser·p0.50:   4.555 ms/op
                 existUser·p0.90:   5.702 ms/op
                 existUser·p0.95:   6.390 ms/op
                 existUser·p0.99:   8.618 ms/op
                 existUser·p0.999:  16.452 ms/op
                 existUser·p0.9999: 26.539 ms/op
                 existUser·p1.00:   27.951 ms/op

Iteration   3: 4.706 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.634 ms/op
                 existUser·p0.50:   4.481 ms/op
                 existUser·p0.90:   5.644 ms/op
                 existUser·p0.95:   6.554 ms/op
                 existUser·p0.99:   9.372 ms/op
                 existUser·p0.999:  23.365 ms/op
                 existUser·p0.9999: 27.952 ms/op
                 existUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 201216
  mean =      4.768 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 84 
    [ 2.500,  5.000) = 150815 
    [ 5.000,  7.500) = 45165 
    [ 7.500, 10.000) = 4050 
    [10.000, 12.500) = 638 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.634 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.759 ms/op
     p(95.0000) =      6.455 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     20.152 ms/op
     p(99.9900) =     27.386 ms/op
     p(99.9990) =     29.094 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.841 ±(99.9%) 0.290 ms/op
# Warmup Iteration   2: 5.720 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.243 ±(99.9%) 0.019 ms/op
Iteration   1: 5.282 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.911 ms/op
                 getUser·p0.50:   4.850 ms/op
                 getUser·p0.90:   6.668 ms/op
                 getUser·p0.95:   8.300 ms/op
                 getUser·p0.99:   12.803 ms/op
                 getUser·p0.999:  22.514 ms/op
                 getUser·p0.9999: 32.497 ms/op
                 getUser·p1.00:   34.537 ms/op

Iteration   2: 4.977 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.640 ms/op
                 getUser·p0.50:   4.653 ms/op
                 getUser·p0.90:   6.087 ms/op
                 getUser·p0.95:   7.487 ms/op
                 getUser·p0.99:   9.781 ms/op
                 getUser·p0.999:  19.268 ms/op
                 getUser·p0.9999: 25.447 ms/op
                 getUser·p1.00:   26.444 ms/op

Iteration   3: 5.085 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.359 ms/op
                 getUser·p0.50:   4.792 ms/op
                 getUser·p0.90:   6.242 ms/op
                 getUser·p0.95:   7.258 ms/op
                 getUser·p0.99:   9.322 ms/op
                 getUser·p0.999:  22.875 ms/op
                 getUser·p0.9999: 25.910 ms/op
                 getUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 187736
  mean =      5.111 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 119035 
    [ 5.000,  7.500) = 58331 
    [ 7.500, 10.000) = 7978 
    [10.000, 12.500) = 1416 
    [12.500, 15.000) = 505 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.640 ms/op
     p(50.0000) =      4.760 ms/op
     p(90.0000) =      6.316 ms/op
     p(95.0000) =      7.651 ms/op
     p(99.0000) =     10.633 ms/op
     p(99.9000) =     22.151 ms/op
     p(99.9900) =     30.482 ms/op
     p(99.9990) =     34.077 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 17.678 ±(99.9%) 0.259 ms/op
# Warmup Iteration   2: 6.720 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.858 ±(99.9%) 0.024 ms/op
Iteration   1: 5.742 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   5.439 ms/op
                 listUser·p0.90:   6.767 ms/op
                 listUser·p0.95:   7.987 ms/op
                 listUser·p0.99:   11.158 ms/op
                 listUser·p0.999:  24.552 ms/op
                 listUser·p0.9999: 38.516 ms/op
                 listUser·p1.00:   39.256 ms/op

Iteration   2: 5.746 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   5.464 ms/op
                 listUser·p0.90:   6.767 ms/op
                 listUser·p0.95:   7.627 ms/op
                 listUser·p0.99:   10.715 ms/op
                 listUser·p0.999:  26.455 ms/op
                 listUser·p0.9999: 29.132 ms/op
                 listUser·p1.00:   30.114 ms/op

Iteration   3: 5.695 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.785 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   6.767 ms/op
                 listUser·p0.95:   7.864 ms/op
                 listUser·p0.99:   11.060 ms/op
                 listUser·p0.999:  19.746 ms/op
                 listUser·p0.9999: 23.267 ms/op
                 listUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 167603
  mean =      5.728 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 35531 
    [ 5.000,  7.500) = 122367 
    [ 7.500, 10.000) = 7104 
    [10.000, 12.500) = 1698 
    [12.500, 15.000) = 362 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      5.431 ms/op
     p(90.0000) =      6.767 ms/op
     p(95.0000) =      7.774 ms/op
     p(99.0000) =     10.960 ms/op
     p(99.9000) =     23.979 ms/op
     p(99.9900) =     36.435 ms/op
     p(99.9990) =     39.123 ms/op
     p(99.9999) =     39.256 ms/op
    p(100.0000) =     39.256 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.219 ± 4.936  ops/ms
ClientPb.existUser                       thrpt       3   6.745 ± 3.105  ops/ms
ClientPb.getUser                         thrpt       3   6.444 ± 4.890  ops/ms
ClientPb.listUser                        thrpt       3   5.605 ± 3.180  ops/ms
ClientPb.createUser                       avgt       3   4.902 ± 0.144   ms/op
ClientPb.existUser                        avgt       3   4.769 ± 0.917   ms/op
ClientPb.getUser                          avgt       3   5.029 ± 1.377   ms/op
ClientPb.listUser                         avgt       3   5.840 ± 1.147   ms/op
ClientPb.createUser                     sample  193516   4.955 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.411           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.710           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.915           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.775           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.617           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.544           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.066           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.443           ms/op
ClientPb.existUser                      sample  201216   4.768 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.634           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.538           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.759           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.455           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.733           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.152           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.386           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.524           ms/op
ClientPb.getUser                        sample  187736   5.111 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.640           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.760           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.316           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.651           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.633           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.151           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.482           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.537           ms/op
ClientPb.listUser                       sample  167603   5.728 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.087           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.431           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.767           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.774           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.960           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.979           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.435           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.256           ms/op
