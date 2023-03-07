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
# Warmup Iteration   1: 2.383 ops/ms
# Warmup Iteration   2: 5.949 ops/ms
# Warmup Iteration   3: 9.343 ops/ms
Iteration   1: 9.920 ops/ms
Iteration   2: 9.927 ops/ms
Iteration   3: 10.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.989 ±(99.9%) 2.077 ops/ms [Average]
  (min, avg, max) = (9.920, 9.989, 10.120), stdev = 0.114
  CI (99.9%): [7.912, 12.066] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.908 ops/ms
# Warmup Iteration   2: 9.214 ops/ms
# Warmup Iteration   3: 10.109 ops/ms
Iteration   1: 10.098 ops/ms
Iteration   2: 10.288 ops/ms
Iteration   3: 9.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.857 ±(99.9%) 10.752 ops/ms [Average]
  (min, avg, max) = (9.185, 9.857, 10.288), stdev = 0.589
  CI (99.9%): [≈ 0, 20.609] (assumes normal distribution)


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
# Warmup Iteration   1: 3.679 ops/ms
# Warmup Iteration   2: 8.950 ops/ms
# Warmup Iteration   3: 9.526 ops/ms
Iteration   1: 9.976 ops/ms
Iteration   2: 10.245 ops/ms
Iteration   3: 10.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.178 ±(99.9%) 3.256 ops/ms [Average]
  (min, avg, max) = (9.976, 10.178, 10.314), stdev = 0.178
  CI (99.9%): [6.922, 13.435] (assumes normal distribution)


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
# Warmup Iteration   1: 3.267 ops/ms
# Warmup Iteration   2: 7.937 ops/ms
# Warmup Iteration   3: 8.254 ops/ms
Iteration   1: 8.631 ops/ms
Iteration   2: 8.501 ops/ms
Iteration   3: 8.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.624 ±(99.9%) 2.191 ops/ms [Average]
  (min, avg, max) = (8.501, 8.624, 8.740), stdev = 0.120
  CI (99.9%): [6.433, 10.815] (assumes normal distribution)


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
# Warmup Iteration   1: 8.260 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.581 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.006 ms/op
Iteration   1: 3.233 ±(99.9%) 0.003 ms/op
Iteration   2: 3.149 ±(99.9%) 0.006 ms/op
Iteration   3: 3.105 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.162 ±(99.9%) 1.181 ms/op [Average]
  (min, avg, max) = (3.105, 3.162, 3.233), stdev = 0.065
  CI (99.9%): [1.981, 4.344] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.460 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.001 ms/op
Iteration   1: 2.998 ±(99.9%) 0.002 ms/op
Iteration   2: 2.998 ±(99.9%) 0.002 ms/op
Iteration   3: 2.977 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.991 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (2.977, 2.991, 2.998), stdev = 0.012
  CI (99.9%): [2.774, 3.208] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.243 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.427 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.003 ms/op
Iteration   1: 3.112 ±(99.9%) 0.003 ms/op
Iteration   2: 3.162 ±(99.9%) 0.005 ms/op
Iteration   3: 3.113 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.129 ±(99.9%) 0.519 ms/op [Average]
  (min, avg, max) = (3.112, 3.129, 3.162), stdev = 0.028
  CI (99.9%): [2.610, 3.648] (assumes normal distribution)


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
# Warmup Iteration   1: 8.956 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.125 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.837 ±(99.9%) 0.008 ms/op
Iteration   1: 3.699 ±(99.9%) 0.006 ms/op
Iteration   2: 3.729 ±(99.9%) 0.004 ms/op
Iteration   3: 3.710 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.713 ±(99.9%) 0.278 ms/op [Average]
  (min, avg, max) = (3.699, 3.713, 3.729), stdev = 0.015
  CI (99.9%): [3.435, 3.990] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.119 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.495 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.008 ms/op
Iteration   1: 3.252 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.046 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  12.616 ms/op
                 createUser·p0.9999: 18.291 ms/op
                 createUser·p1.00:   19.169 ms/op

Iteration   2: 3.225 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  10.713 ms/op
                 createUser·p0.9999: 22.154 ms/op
                 createUser·p1.00:   22.675 ms/op

Iteration   3: 3.140 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  16.663 ms/op
                 createUser·p0.9999: 20.152 ms/op
                 createUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299241
  mean =      3.205 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20509 
    [ 2.500,  5.000) = 272200 
    [ 5.000,  7.500) = 5439 
    [ 7.500, 10.000) = 623 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     16.253 ms/op
     p(99.9900) =     20.659 ms/op
     p(99.9990) =     22.699 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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
# Warmup Iteration   1: 6.566 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
Iteration   1: 3.083 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  12.045 ms/op
                 existUser·p0.9999: 18.153 ms/op
                 existUser·p1.00:   19.497 ms/op

Iteration   2: 3.205 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.382 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   5.606 ms/op
                 existUser·p0.999:  9.552 ms/op
                 existUser·p0.9999: 20.318 ms/op
                 existUser·p1.00:   21.103 ms/op

Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.544 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.310 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  9.007 ms/op
                 existUser·p0.9999: 20.739 ms/op
                 existUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308840
  mean =      3.107 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21111 
    [ 2.500,  5.000) = 283215 
    [ 5.000,  7.500) = 3897 
    [ 7.500, 10.000) = 305 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     10.177 ms/op
     p(99.9900) =     20.382 ms/op
     p(99.9990) =     21.427 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 7.696 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.508 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.197 ±(99.9%) 0.009 ms/op
Iteration   1: 3.282 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  18.230 ms/op
                 getUser·p0.9999: 20.775 ms/op
                 getUser·p1.00:   23.855 ms/op

Iteration   2: 3.268 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.362 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.554 ms/op
                 getUser·p0.999:  10.830 ms/op
                 getUser·p0.9999: 21.529 ms/op
                 getUser·p1.00:   22.020 ms/op

Iteration   3: 3.331 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.655 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  17.145 ms/op
                 getUser·p0.9999: 26.339 ms/op
                 getUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291664
  mean =      3.293 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21714 
    [ 2.500,  5.000) = 258646 
    [ 5.000,  7.500) = 10271 
    [ 7.500, 10.000) = 618 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 178 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.423 ms/op
     p(99.9000) =     18.143 ms/op
     p(99.9900) =     24.773 ms/op
     p(99.9990) =     26.875 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


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
# Warmup Iteration   1: 8.225 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.173 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.768 ±(99.9%) 0.011 ms/op
Iteration   1: 3.670 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.513 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.964 ms/op
                 listUser·p0.999:  17.132 ms/op
                 listUser·p0.9999: 24.113 ms/op
                 listUser·p1.00:   26.739 ms/op

Iteration   2: 3.731 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.542 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  12.861 ms/op
                 listUser·p0.9999: 18.771 ms/op
                 listUser·p1.00:   19.694 ms/op

Iteration   3: 3.738 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.681 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  13.763 ms/op
                 listUser·p0.9999: 15.434 ms/op
                 listUser·p1.00:   15.778 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258448
  mean =      3.713 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 250597 
    [ 5.000,  7.500) = 5888 
    [ 7.500, 10.000) = 1195 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 293 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.513 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.976 ms/op
     p(99.9000) =     13.992 ms/op
     p(99.9900) =     21.440 ms/op
     p(99.9990) =     25.936 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   9.989 ±  2.077  ops/ms
ClientPb.existUser                       thrpt       3   9.857 ± 10.752  ops/ms
ClientPb.getUser                         thrpt       3  10.178 ±  3.256  ops/ms
ClientPb.listUser                        thrpt       3   8.624 ±  2.191  ops/ms
ClientPb.createUser                       avgt       3   3.162 ±  1.181   ms/op
ClientPb.existUser                        avgt       3   2.991 ±  0.217   ms/op
ClientPb.getUser                          avgt       3   3.129 ±  0.519   ms/op
ClientPb.listUser                         avgt       3   3.713 ±  0.278   ms/op
ClientPb.createUser                     sample  299241   3.205 ±  0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.046            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.150            ms/op
ClientPb.createUser:createUser·p0.90    sample           3.584            ms/op
ClientPb.createUser:createUser·p0.95    sample           3.920            ms/op
ClientPb.createUser:createUser·p0.99    sample           5.579            ms/op
ClientPb.createUser:createUser·p0.999   sample          16.253            ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.659            ms/op
ClientPb.createUser:createUser·p1.00    sample          26.477            ms/op
ClientPb.existUser                      sample  308840   3.107 ±  0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.137            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.424            ms/op
ClientPb.existUser:existUser·p0.95      sample           3.756            ms/op
ClientPb.existUser:existUser·p0.99      sample           5.308            ms/op
ClientPb.existUser:existUser·p0.999     sample          10.177            ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.382            ms/op
ClientPb.existUser:existUser·p1.00      sample          21.496            ms/op
ClientPb.getUser                        sample  291664   3.293 ±  0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.031            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174            ms/op
ClientPb.getUser:getUser·p0.90          sample           3.797            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.497            ms/op
ClientPb.getUser:getUser·p0.99          sample           6.423            ms/op
ClientPb.getUser:getUser·p0.999         sample          18.143            ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.773            ms/op
ClientPb.getUser:getUser·p1.00          sample          27.099            ms/op
ClientPb.listUser                       sample  258448   3.713 ±  0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.513            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.641            ms/op
ClientPb.listUser:listUser·p0.90        sample           3.981            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301            ms/op
ClientPb.listUser:listUser·p0.99        sample           6.976            ms/op
ClientPb.listUser:listUser·p0.999       sample          13.992            ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.440            ms/op
ClientPb.listUser:listUser·p1.00        sample          26.739            ms/op
