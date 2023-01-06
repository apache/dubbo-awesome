# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.591 ops/ms
# Warmup Iteration   2: 4.066 ops/ms
# Warmup Iteration   3: 7.447 ops/ms
Iteration   1: 7.742 ops/ms
Iteration   2: 8.505 ops/ms
Iteration   3: 8.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.214 ±(99.9%) 7.521 ops/ms [Average]
  (min, avg, max) = (7.742, 8.214, 8.505), stdev = 0.412
  CI (99.9%): [0.692, 15.735] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.520 ops/ms
# Warmup Iteration   2: 7.521 ops/ms
# Warmup Iteration   3: 8.352 ops/ms
Iteration   1: 8.383 ops/ms
Iteration   2: 8.633 ops/ms
Iteration   3: 8.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.468 ±(99.9%) 2.601 ops/ms [Average]
  (min, avg, max) = (8.383, 8.468, 8.633), stdev = 0.143
  CI (99.9%): [5.867, 11.069] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.406 ops/ms
# Warmup Iteration   2: 6.945 ops/ms
# Warmup Iteration   3: 8.063 ops/ms
Iteration   1: 8.409 ops/ms
Iteration   2: 8.379 ops/ms
Iteration   3: 8.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.360 ±(99.9%) 1.107 ops/ms [Average]
  (min, avg, max) = (8.292, 8.360, 8.409), stdev = 0.061
  CI (99.9%): [7.253, 9.467] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.293 ops/ms
# Warmup Iteration   2: 6.074 ops/ms
# Warmup Iteration   3: 6.849 ops/ms
Iteration   1: 6.869 ops/ms
Iteration   2: 6.824 ops/ms
Iteration   3: 6.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.840 ±(99.9%) 0.448 ops/ms [Average]
  (min, avg, max) = (6.824, 6.840, 6.869), stdev = 0.025
  CI (99.9%): [6.393, 7.288] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.398 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.364 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.042 ±(99.9%) 0.009 ms/op
Iteration   1: 3.883 ±(99.9%) 0.009 ms/op
Iteration   2: 3.841 ±(99.9%) 0.013 ms/op
Iteration   3: 3.799 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.841 ±(99.9%) 0.769 ms/op [Average]
  (min, avg, max) = (3.799, 3.841, 3.883), stdev = 0.042
  CI (99.9%): [3.072, 4.609] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.545 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.261 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.007 ms/op
Iteration   1: 3.718 ±(99.9%) 0.011 ms/op
Iteration   2: 3.639 ±(99.9%) 0.011 ms/op
Iteration   3: 3.783 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.714 ±(99.9%) 1.313 ms/op [Average]
  (min, avg, max) = (3.639, 3.714, 3.783), stdev = 0.072
  CI (99.9%): [2.401, 5.026] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.365 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.676 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.922 ±(99.9%) 0.009 ms/op
Iteration   1: 3.948 ±(99.9%) 0.002 ms/op
Iteration   2: 3.852 ±(99.9%) 0.006 ms/op
Iteration   3: 3.920 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.907 ±(99.9%) 0.910 ms/op [Average]
  (min, avg, max) = (3.852, 3.907, 3.948), stdev = 0.050
  CI (99.9%): [2.996, 4.817] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.891 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.577 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.767 ±(99.9%) 0.010 ms/op
Iteration   1: 4.846 ±(99.9%) 0.006 ms/op
Iteration   2: 4.782 ±(99.9%) 0.008 ms/op
Iteration   3: 4.598 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.742 ±(99.9%) 2.352 ms/op [Average]
  (min, avg, max) = (4.598, 4.742, 4.846), stdev = 0.129
  CI (99.9%): [2.390, 7.094] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.240 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.804 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.514 ±(99.9%) 0.020 ms/op
Iteration   1: 3.911 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.751 ms/op
                 createUser·p0.50:   3.695 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   7.307 ms/op
                 createUser·p0.999:  22.280 ms/op
                 createUser·p0.9999: 25.596 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   2: 4.108 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.827 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   4.825 ms/op
                 createUser·p0.95:   5.267 ms/op
                 createUser·p0.99:   7.176 ms/op
                 createUser·p0.999:  13.944 ms/op
                 createUser·p0.9999: 37.841 ms/op
                 createUser·p1.00:   38.732 ms/op

Iteration   3: 3.781 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  28.597 ms/op
                 createUser·p0.9999: 35.591 ms/op
                 createUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 244345
  mean =      3.929 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 550 
    [ 2.500,  5.000) = 231847 
    [ 5.000,  7.500) = 10200 
    [ 7.500, 10.000) = 982 
    [10.000, 12.500) = 372 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     22.151 ms/op
     p(99.9900) =     36.504 ms/op
     p(99.9990) =     38.521 ms/op
     p(99.9999) =     38.732 ms/op
    p(100.0000) =     38.732 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 12.571 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.260 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.714 ±(99.9%) 0.011 ms/op
Iteration   1: 3.669 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.524 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  22.408 ms/op
                 existUser·p0.9999: 24.880 ms/op
                 existUser·p1.00:   25.461 ms/op

Iteration   2: 3.577 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.423 ms/op
                 existUser·p0.50:   3.510 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   5.864 ms/op
                 existUser·p0.999:  12.001 ms/op
                 existUser·p0.9999: 27.822 ms/op
                 existUser·p1.00:   30.081 ms/op

Iteration   3: 3.684 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.778 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   4.145 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   6.603 ms/op
                 existUser·p0.999:  25.205 ms/op
                 existUser·p0.9999: 31.289 ms/op
                 existUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 263448
  mean =      3.643 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 721 
    [ 2.500,  5.000) = 255167 
    [ 5.000,  7.500) = 6270 
    [ 7.500, 10.000) = 767 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.423 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     13.027 ms/op
     p(99.9900) =     28.857 ms/op
     p(99.9990) =     31.803 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.806 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.450 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.122 ±(99.9%) 0.014 ms/op
Iteration   1: 4.016 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.290 ms/op
                 getUser·p0.50:   3.813 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.226 ms/op
                 getUser·p0.99:   7.791 ms/op
                 getUser·p0.999:  23.928 ms/op
                 getUser·p0.9999: 28.706 ms/op
                 getUser·p1.00:   30.441 ms/op

Iteration   2: 3.853 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   3.682 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  25.430 ms/op
                 getUser·p0.9999: 29.465 ms/op
                 getUser·p1.00:   34.931 ms/op

Iteration   3: 3.804 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.034 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   7.004 ms/op
                 getUser·p0.999:  12.447 ms/op
                 getUser·p0.9999: 34.445 ms/op
                 getUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 246832
  mean =      3.889 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 331 
    [ 2.500,  5.000) = 234010 
    [ 5.000,  7.500) = 10372 
    [ 7.500, 10.000) = 1436 
    [10.000, 12.500) = 309 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 38 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     23.620 ms/op
     p(99.9900) =     33.706 ms/op
     p(99.9990) =     34.734 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.955 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 5.322 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.681 ±(99.9%) 0.016 ms/op
Iteration   1: 4.648 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.677 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  25.887 ms/op
                 listUser·p0.9999: 32.051 ms/op
                 listUser·p1.00:   32.801 ms/op

Iteration   2: 4.719 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 22.099 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   3: 4.558 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.650 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   8.217 ms/op
                 listUser·p0.999:  16.564 ms/op
                 listUser·p0.9999: 21.885 ms/op
                 listUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 206822
  mean =      4.641 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 174128 
    [ 5.000,  7.500) = 27884 
    [ 7.500, 10.000) = 3837 
    [10.000, 12.500) = 478 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.677 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      8.503 ms/op
     p(99.9000) =     19.765 ms/op
     p(99.9900) =     30.873 ms/op
     p(99.9990) =     32.429 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.214 ± 7.521  ops/ms
ClientPb.existUser                       thrpt       3   8.468 ± 2.601  ops/ms
ClientPb.getUser                         thrpt       3   8.360 ± 1.107  ops/ms
ClientPb.listUser                        thrpt       3   6.840 ± 0.448  ops/ms
ClientPb.createUser                       avgt       3   3.841 ± 0.769   ms/op
ClientPb.existUser                        avgt       3   3.714 ± 1.313   ms/op
ClientPb.getUser                          avgt       3   3.907 ± 0.910   ms/op
ClientPb.listUser                         avgt       3   4.742 ± 2.352   ms/op
ClientPb.createUser                     sample  244345   3.929 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.438           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.588           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.989           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.996           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.151           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.504           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.732           ms/op
ClientPb.existUser                      sample  263448   3.643 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.423           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.059           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.407           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.488           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.027           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.857           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.014           ms/op
ClientPb.getUser                        sample  246832   3.889 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.290           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.695           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.022           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.234           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.620           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.706           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.931           ms/op
ClientPb.listUser                       sample  206822   4.641 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.677           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.503           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.765           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.873           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.801           ms/op
