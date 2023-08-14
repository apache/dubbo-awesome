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
# Warmup Iteration   1: 1.486 ops/ms
# Warmup Iteration   2: 3.918 ops/ms
# Warmup Iteration   3: 6.225 ops/ms
Iteration   1: 6.166 ops/ms
Iteration   2: 6.947 ops/ms
Iteration   3: 6.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.654 ±(99.9%) 7.771 ops/ms [Average]
  (min, avg, max) = (6.166, 6.654, 6.947), stdev = 0.426
  CI (99.9%): [≈ 0, 14.425] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.213 ops/ms
# Warmup Iteration   2: 6.121 ops/ms
# Warmup Iteration   3: 6.544 ops/ms
Iteration   1: 6.952 ops/ms
Iteration   2: 7.042 ops/ms
Iteration   3: 6.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.931 ±(99.9%) 2.249 ops/ms [Average]
  (min, avg, max) = (6.799, 6.931, 7.042), stdev = 0.123
  CI (99.9%): [4.682, 9.180] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.404 ops/ms
# Warmup Iteration   2: 6.114 ops/ms
# Warmup Iteration   3: 6.703 ops/ms
Iteration   1: 6.553 ops/ms
Iteration   2: 6.770 ops/ms
Iteration   3: 6.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.657 ±(99.9%) 1.982 ops/ms [Average]
  (min, avg, max) = (6.553, 6.657, 6.770), stdev = 0.109
  CI (99.9%): [4.675, 8.639] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.929 ops/ms
# Warmup Iteration   2: 4.907 ops/ms
# Warmup Iteration   3: 5.621 ops/ms
Iteration   1: 5.610 ops/ms
Iteration   2: 5.764 ops/ms
Iteration   3: 5.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.714 ±(99.9%) 1.641 ops/ms [Average]
  (min, avg, max) = (5.610, 5.714, 5.767), stdev = 0.090
  CI (99.9%): [4.072, 7.355] (assumes normal distribution)


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
# Warmup Iteration   1: 13.747 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.550 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.106 ±(99.9%) 0.013 ms/op
Iteration   1: 4.776 ±(99.9%) 0.019 ms/op
Iteration   2: 4.902 ±(99.9%) 0.011 ms/op
Iteration   3: 4.913 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.863 ±(99.9%) 1.389 ms/op [Average]
  (min, avg, max) = (4.776, 4.863, 4.913), stdev = 0.076
  CI (99.9%): [3.474, 6.253] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 12.580 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.085 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.843 ±(99.9%) 0.005 ms/op
Iteration   1: 4.729 ±(99.9%) 0.008 ms/op
Iteration   2: 4.472 ±(99.9%) 0.012 ms/op
Iteration   3: 4.684 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.629 ±(99.9%) 2.503 ms/op [Average]
  (min, avg, max) = (4.472, 4.629, 4.729), stdev = 0.137
  CI (99.9%): [2.126, 7.132] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 13.146 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.237 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.038 ±(99.9%) 0.009 ms/op
Iteration   1: 4.927 ±(99.9%) 0.010 ms/op
Iteration   2: 4.914 ±(99.9%) 0.010 ms/op
Iteration   3: 5.074 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.972 ±(99.9%) 1.624 ms/op [Average]
  (min, avg, max) = (4.914, 4.972, 5.074), stdev = 0.089
  CI (99.9%): [3.347, 6.596] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 14.689 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 6.479 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.539 ±(99.9%) 0.013 ms/op
Iteration   1: 6.050 ±(99.9%) 0.010 ms/op
Iteration   2: 5.399 ±(99.9%) 0.013 ms/op
Iteration   3: 5.558 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.669 ±(99.9%) 6.186 ms/op [Average]
  (min, avg, max) = (5.399, 5.669, 6.050), stdev = 0.339
  CI (99.9%): [≈ 0, 11.855] (assumes normal distribution)


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
# Warmup Iteration   1: 14.738 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 5.552 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.233 ±(99.9%) 0.021 ms/op
Iteration   1: 5.006 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.896 ms/op
                 createUser·p0.50:   4.801 ms/op
                 createUser·p0.90:   6.128 ms/op
                 createUser·p0.95:   6.873 ms/op
                 createUser·p0.99:   9.339 ms/op
                 createUser·p0.999:  22.267 ms/op
                 createUser·p0.9999: 28.274 ms/op
                 createUser·p1.00:   29.000 ms/op

Iteration   2: 4.987 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.054 ms/op
                 createUser·p0.50:   4.719 ms/op
                 createUser·p0.90:   6.169 ms/op
                 createUser·p0.95:   6.971 ms/op
                 createUser·p0.99:   9.617 ms/op
                 createUser·p0.999:  22.705 ms/op
                 createUser·p0.9999: 27.026 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   3: 4.916 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.101 ms/op
                 createUser·p0.50:   4.669 ms/op
                 createUser·p0.90:   6.054 ms/op
                 createUser·p0.95:   6.775 ms/op
                 createUser·p0.99:   9.503 ms/op
                 createUser·p0.999:  19.330 ms/op
                 createUser·p0.9999: 28.704 ms/op
                 createUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 193045
  mean =      4.969 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 109 
    [ 2.500,  5.000) = 120163 
    [ 5.000,  7.500) = 66628 
    [ 7.500, 10.000) = 4637 
    [10.000, 12.500) = 1038 
    [12.500, 15.000) = 257 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 104 

  Percentiles, ms/op:
      p(0.0000) =      1.896 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      6.119 ms/op
     p(95.0000) =      6.873 ms/op
     p(99.0000) =      9.470 ms/op
     p(99.9000) =     19.431 ms/op
     p(99.9900) =     28.312 ms/op
     p(99.9990) =     29.250 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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
# Warmup Iteration   1: 11.259 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 5.004 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.691 ±(99.9%) 0.015 ms/op
Iteration   1: 4.900 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.142 ms/op
                 existUser·p0.50:   4.522 ms/op
                 existUser·p0.90:   6.472 ms/op
                 existUser·p0.95:   7.496 ms/op
                 existUser·p0.99:   10.104 ms/op
                 existUser·p0.999:  16.985 ms/op
                 existUser·p0.9999: 24.696 ms/op
                 existUser·p1.00:   27.099 ms/op

Iteration   2: 4.504 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.358 ms/op
                 existUser·p0.50:   4.276 ms/op
                 existUser·p0.90:   5.448 ms/op
                 existUser·p0.95:   6.070 ms/op
                 existUser·p0.99:   8.503 ms/op
                 existUser·p0.999:  15.512 ms/op
                 existUser·p0.9999: 30.835 ms/op
                 existUser·p1.00:   33.817 ms/op

Iteration   3: 4.681 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.927 ms/op
                 existUser·p0.50:   4.432 ms/op
                 existUser·p0.90:   5.702 ms/op
                 existUser·p0.95:   6.545 ms/op
                 existUser·p0.99:   9.486 ms/op
                 existUser·p0.999:  14.085 ms/op
                 existUser·p0.9999: 30.846 ms/op
                 existUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 204693
  mean =      4.690 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 98 
    [ 2.500,  5.000) = 155001 
    [ 5.000,  7.500) = 43260 
    [ 7.500, 10.000) = 4837 
    [10.000, 12.500) = 1054 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.358 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.857 ms/op
     p(95.0000) =      6.799 ms/op
     p(99.0000) =      9.454 ms/op
     p(99.9000) =     16.176 ms/op
     p(99.9900) =     30.688 ms/op
     p(99.9990) =     32.042 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 11.658 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 5.373 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.074 ±(99.9%) 0.017 ms/op
Iteration   1: 5.120 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.535 ms/op
                 getUser·p0.50:   4.710 ms/op
                 getUser·p0.90:   6.529 ms/op
                 getUser·p0.95:   8.077 ms/op
                 getUser·p0.99:   11.960 ms/op
                 getUser·p0.999:  25.282 ms/op
                 getUser·p0.9999: 29.074 ms/op
                 getUser·p1.00:   29.721 ms/op

Iteration   2: 5.109 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.995 ms/op
                 getUser·p0.50:   4.850 ms/op
                 getUser·p0.90:   6.275 ms/op
                 getUser·p0.95:   7.283 ms/op
                 getUser·p0.99:   9.803 ms/op
                 getUser·p0.999:  27.394 ms/op
                 getUser·p0.9999: 32.670 ms/op
                 getUser·p1.00:   34.406 ms/op

Iteration   3: 4.815 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.821 ms/op
                 getUser·p0.50:   4.555 ms/op
                 getUser·p0.90:   5.825 ms/op
                 getUser·p0.95:   6.803 ms/op
                 getUser·p0.99:   9.617 ms/op
                 getUser·p0.999:  16.546 ms/op
                 getUser·p0.9999: 31.097 ms/op
                 getUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 191484
  mean =      5.011 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 123670 
    [ 5.000,  7.500) = 58754 
    [ 7.500, 10.000) = 6478 
    [10.000, 12.500) = 1642 
    [12.500, 15.000) = 551 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 90 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.821 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      6.169 ms/op
     p(95.0000) =      7.389 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     25.347 ms/op
     p(99.9900) =     31.846 ms/op
     p(99.9990) =     34.227 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 15.201 ±(99.9%) 0.236 ms/op
# Warmup Iteration   2: 6.337 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.958 ±(99.9%) 0.024 ms/op
Iteration   1: 5.819 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   5.538 ms/op
                 listUser·p0.90:   6.849 ms/op
                 listUser·p0.95:   8.069 ms/op
                 listUser·p0.99:   11.845 ms/op
                 listUser·p0.999:  26.869 ms/op
                 listUser·p0.9999: 29.114 ms/op
                 listUser·p1.00:   31.031 ms/op

Iteration   2: 5.787 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.683 ms/op
                 listUser·p0.50:   5.448 ms/op
                 listUser·p0.90:   6.996 ms/op
                 listUser·p0.95:   8.053 ms/op
                 listUser·p0.99:   11.649 ms/op
                 listUser·p0.999:  27.853 ms/op
                 listUser·p0.9999: 33.125 ms/op
                 listUser·p1.00:   33.554 ms/op

Iteration   3: 5.462 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.894 ms/op
                 listUser·p0.50:   5.169 ms/op
                 listUser·p0.90:   6.463 ms/op
                 listUser·p0.95:   7.520 ms/op
                 listUser·p0.99:   11.665 ms/op
                 listUser·p0.999:  21.371 ms/op
                 listUser·p0.9999: 24.117 ms/op
                 listUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 168862
  mean =      5.684 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 47746 
    [ 5.000,  7.500) = 110522 
    [ 7.500, 10.000) = 7279 
    [10.000, 12.500) = 1964 
    [12.500, 15.000) = 741 
    [15.000, 17.500) = 264 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.894 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      6.791 ms/op
     p(95.0000) =      7.889 ms/op
     p(99.0000) =     11.665 ms/op
     p(99.9000) =     24.618 ms/op
     p(99.9900) =     32.706 ms/op
     p(99.9990) =     33.509 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.654 ± 7.771  ops/ms
ClientPb.existUser                       thrpt       3   6.931 ± 2.249  ops/ms
ClientPb.getUser                         thrpt       3   6.657 ± 1.982  ops/ms
ClientPb.listUser                        thrpt       3   5.714 ± 1.641  ops/ms
ClientPb.createUser                       avgt       3   4.863 ± 1.389   ms/op
ClientPb.existUser                        avgt       3   4.629 ± 2.503   ms/op
ClientPb.getUser                          avgt       3   4.972 ± 1.624   ms/op
ClientPb.listUser                         avgt       3   5.669 ± 6.186   ms/op
ClientPb.createUser                     sample  193045   4.969 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.896           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.735           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.119           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.873           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.470           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.431           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.312           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.524           ms/op
ClientPb.existUser                      sample  204693   4.690 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.358           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.399           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.857           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.799           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.454           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.176           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.688           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.817           ms/op
ClientPb.getUser                        sample  191484   5.011 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.821           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.702           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.169           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.389           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.617           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.347           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.846           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.406           ms/op
ClientPb.listUser                       sample  168862   5.684 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.894           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.374           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.791           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.889           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.665           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.618           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.706           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.554           ms/op
